---
title: "Inception (2010)"
poster: "[https://image.tmdb.org/t/p/w500/qmDpIHrmpJINaRKAfWQfftjCdyi.jpg](https://www.imdb.com/title/tt1375666/mediaviewer/rm3426651392/?ref_=tt_ov_i)"
imdb: 8.8
rotten: 87%
director: Christopher Nolan
cast: Leonardo DiCaprio, Joseph Gordon-Levitt, Ellen Page, Tom Hardy, Cillian Murphy, 
review: "Mind-bending and visually stunning. Loved the concept of dream layers."
favorite: yes
---

# 🎬 {{ page.title }}

![Poster]({{ page.poster }})

**IMDb:** ⭐ {{ page.imdb }}  
**Rotten Tomatoes:** 🍅 {{ page.rotten }}  
**Director:** 🎥 {{ page.director }}  
**Cast:** 👥 {{ page.cast }}

---

## 📝 My Review
> {{ page.review }}

{% if page.favorite == "yes" %}
💖 **This is one of my favorites!**
{% endif %}
