---
layout: ieeevr-default
title: "Posters"
subtitle: "IEEE VR 2026"
title_separator: "|"
---

<p style="width:100%; margin: 30px auto; padding: 20px 0; text-align:center; font-size:1rem; border-radius: 30px; background-color: #f3f3f3">This content is currently being updated.</p>
<div style="display:none">
<h1>Posters</h1>
<div>
<p> <b>Each day, talk with the authors: 9:30‑10:00, 13:15‑14:00, 16:15‑17:15 (Timezone: Saint-Malo, France UTC+1)</b> 
    <b><strong style="color:red">On Monday, talk with the authors: 10:45‑11:15, 13:00‑13:45, 16:00‑17:00 (Timezone: Saint-Malo, France UTC+1)</strong></b>
</p>

    <table class="styled-table">
        <tr>
            {% for day in site.data.postersDays %}
                <tr>
                    <th colspan="4"><a href="#{{ day.id }}" style="color:white">{{ day.day}} posters</a></th>
                </tr>
                {% assign category_file = day.name %}
                {% for cat in site.data[category_file] %}
                    <tr>
                        <td><a href="#{{ cat.id }}">{{ cat.name }}</a></td>
                    </tr>
                {% endfor %}
            {% endfor %}    
        </tr>
    </table>
</div>
<div>    
    {% for day in site.data.postersDays %}
    <div>
        <h1 id="{{ day.id }}" class="pink" style="padding-top:25px;">{{ day.day}} posters</h1>  
        {% assign category_file = day.name %}  
        {% assign poster_file = day.posters %}
        {% for cat in site.data[category_file] %}
            <h2 id="{{ cat.id }}" class="pink" style="padding-top:25px;">{{ cat.name }} </h2>  
            {% for poster in site.data.[poster_file] %}
                {% if poster.PosterCategory == cat.name %}
                    <div style="margin-left: 25px;">     
                        {% for a in site.data.awards %}  
                            {% if a.type == 'Poster' %}
                                {% if a.id == poster.BoothID %}
                                    {% if a.award == 'Best Poster' %}
                                        <div class="align-left"><a href="{{ "/awards/conference-awards" | relative_url }}#poster-best"><img src= "{{ "/assets/images/awards/best.png" | relative_url }}" title="Best Poster Award" alt="Best Poster Award"></a></div>
                                    {% endif %}                                                    
                                    {% if a.award == "Honorable Mention" %}
                                        <div class="align-left"><a href="{{ "/awards/conference-awards" | relative_url }}#poster-honorable"><img src= "{{ "/assets/images/awards/hm.png" | relative_url }}" title="Best Poster Honorable Mention" alt="Best Poster Honorable Mention"></a></div>
                                    {% endif %}
                                {% endif %}
                            {% endif %}
                        {% endfor %}                               
                        <p class="medLarge" id="{{ paper.id }}" style="margin-bottom: 0.3em;">
                            <strong>{{ poster.title }} (Booth ID: {{ poster.BoothID }}) </strong>
                        </p>
                        <p class="font_70" >
                            {% assign authornames = poster.authors | split: ";" %}
                            {% for name in authornames %}
                                {% assign barename = name | split: ":" %}
                                {% for n in barename %}
                                    {% if n == barename.last %}
                                        <i>{{ n | strip }}{% if name == authornames.last %}{% else %};{% endif %}</i>
                                    {% else %}                            
                                        <span class="bold">{{ n | strip }},</span>
                                    {% endif %}
                                {% endfor %} 
                            {% endfor %}
                        </p>
                        {% if poster.abstract %}
                            <div id="abstract_{{ poster.VideoLink }}" class="wrap-collabsible" style="margin-top: 0px; padding-top: 0px; margin-bottom: 0px;"> <input id="collapsibleabstract{{ poster.VideoLink }}" class="toggle" type="checkbox"> 
                                <label for="collapsibleabstract{{ poster.VideoLink }}" class="lbl-toggle">Abstract</label>
                                <div class="collapsible-content">
                                    <div class="content-inner">
                                        <p>{{ poster.abstract }}</p>
                                    </div>
                                </div>
                            </div>   
                        {% endif %}
                        {% if poster.VideoLink %}
                        <div id="video_{{ poster.VideoLink }}" class="wrap-collabsible" style="margin-top: 0px; padding-top: 0px; margin-bottom: 0px;"> <input id="collapsiblevideo{{ poster.VideoLink }}" class="toggle" type="checkbox"> 
                            <label for="collapsiblevideo{{ poster.VideoLink }}" class="lbl-toggle">Video</label>
                            <div class="collapsible-content">
                                <div class="content-inner">
                                    <div class="video-container">
                                        <iframe src="https://www.youtube.com/embed/{{ poster.VideoLink }}" loading="lazy" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                                    </div>
                                </div>
                            </div>
                        </div>                           
                        {% endif %}
                    </div>
                {% endif %}
            {% endfor %}            
            {% assign j = 0 %}
            {% for poster in site.data.postersDC %}
                {% if poster.PosterCategory == cat.name %}
                    {% if j == 0 %}
                        {% assign j = 1 %}
                        <h3> Doctoral Consortium Posters </h3>
                    {% endif %}
                    {% for dc in site.data.dc %}
                        {% if dc.id == poster.id %}
                            <div style="margin-left: 25px;">                                  
                                <p class="medLarge" id="{{ paper.id }}" style="margin-bottom: 0.3em;">
                                    <strong>{{ poster.title }} (Booth ID: {{ poster.BoothID }}) </strong>
                                </p>
                                <p class="font_70">
                                    <span class="bold">{{ dc.name | strip }}</span>, <i>{{ dc.affiliation | strip }}</i><br />
                                </p>
                                {% if poster.abstract %}
                                    <div id="abstract_{{ poster.BoothID }}" class="wrap-collabsible" style="margin-top: 0px; padding-top: 0px; margin-bottom: 0px;"> <input id="collapsibleabstract{{ poster.BoothID }}" class="toggle" type="checkbox"> 
                                        <label for="collapsibleabstract{{ poster.BoothID }}" class="lbl-toggle">Abstract</label>
                                        <div class="collapsible-content">
                                            <div class="content-inner">
                                                <p>{{ poster.abstract }}</p>
                                            </div>
                                        </div>
                                    </div>   
                                {% endif %}
                            </div>                    
                        {% endif %}
                    {% endfor %}
                {% endif %}
            {% endfor %}
        {% endfor %}
    </div>
    {% endfor %}
</div>

</div>
