# Pokecss - Dragonite

Dragonite made for the #Pokecss challenge that takes place on twitter!

**SITE:** [https://hectormr206.github.io/pokecss-dragonite/](https://hectormr206.github.io/pokecss-dragonite/)

![Preview](.readme-static/preview.png)

## 🚀 Developing

It was developed with 3 main CSS properties:
It was developed with 3 main CSS properties:
* clip-path: polygon
```
clip-path: polygon (50% 0, 80% 90%, 20% 90%);
# The coordinates to use are written, each coordinate is a point and CSS draws based on those points.
# She helped me make the dragonite body and all its contours.
```
* clip-path: ellipse
```
clip-path: ellipse (50% 40% at 50% 50%);
# The first value is how much the X axis will have, that is horizontally, while the second value is on the Y axis that is, vertically. Then we put "at" followed by the position of the ellipse, this can be in keywords (top, bottom, right, left) or using percentages, but not both.
# Helping me to make the eyes.
```
* filter: drop-shadow 
```
filter: drop-shadow(2px 0px 0px var (- border-color))
     drop-shadow (-2px 0px 0px var (- border-color))
     drop-shadow (0px 2px 0px var (- border-color))
     drop-shadow (0px -2px 0px var (- border-color));
# Add 4 shadows distributed at the top, bottom, left and right.
# Helping to make the black outline of the pokemon.
```

## 🧾 License

The MIT License (MIT)

## 💻 Technologies

- HTML
- CSS

## 📖 Reference
* [https://www.youtube.com/watch?v=IP3OmWpUuIg](https://www.youtube.com/watch?v=IP3OmWpUuIg)
* [https://medium.com/@carlacentenor/dibujando-con-css-y-html-nivel-beginner-b6ed7103e627](https://medium.com/@carlacentenor/dibujando-con-css-y-html-nivel-beginner-b6ed7103e627)
* [https://github.com/mariwrios/pokecss-mew](https://github.com/mariwrios/pokecss-mew)
* [https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow)
* [https://bennettfeely.com/clippy/](https://bennettfeely.com/clippy/)
* [https://codepen.io/jorgemaiden](https://codepen.io/jorgemaiden/pen/ZYRRYy?__cf_chl_jschl_tk__=0af9513012ba133ca735a7f8b396b00735e161d1-1604047040-0-AcLHm5a5Vl10Bk3OqtyNXmwZgpvxl81cYvQK3iYkBVcLCRboqSonJvZbofm_nYWSWS0qTfoFTZq5k0FhIxVwiifxz6ZtDGO9gRKuWgN8jt9HFQRa9VePpz6IrjYoO6fjuda3PibmueYXlVm7HTkqsShpMlCq7jpcQybECC79tkj9BsHlpAjJ_EKK1sYxiZBdglELQEiwvI4wX_jKtcfLOJ14Py2AzD2_NgMzt-CPH9pwmcCdY4q3ghyRdJZDWXsEtYOFWI1x00ilAJEWTKv8Tqew1XeKXAydDzBbU49zbS09-yipzqEAjYNI1C9wM3780eYpCLFZfozw2EbVrlABI_vSDhQCulNBurTvcdAv-r4z)