# my-first-project

мій перший проект
My first project

<img
src="./images/work-at-mob1x.jpg"
alt="portfolio pictxure"
/>

 <picture>
          <source
            srcset="
              ./images/work-at-deckt1x.jpg 1x,
              ./images/work-at-deckt2x.jpg 2x
            "
            media="(min-width: 1158px)"
          />

          <source
            srcset="
              ./images/work-at-mob1x.jpg 1x,
              ./images/work-at-mob2x.jpg 2x
            "
            media="(max-width: 767px)"
          />
          <img
            class="jpg-work"
            src="./images/work-at-deckt1x.jpg"
            alt="work-at"
          />
        </picture>

<svg class="svg-work" width="338" height="311">
          <use href="./images/work-at-mob.svg"></use>
        </svg>
