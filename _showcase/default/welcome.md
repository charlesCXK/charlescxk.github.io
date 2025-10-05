---
show: false
width: 6
date: 2024-01-12 00:01:00 +0800

height: 295px
images:
- src: assets/images/photos/paris/Paris1.jpg
  title: Photo 1
  desc: Description 1.
#   link: https://picsum.photos/
- src: https://picsum.photos/seed/second22/800/800
  title: Photo 2
  desc: Description 2
- src: https://picsum.photos/seed/third33/800/800
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}

<div class="p-4">
    <h2>Something Interesting</h2>
    <hr />
    <p>
        <code>Showcase</code> is a page where you can show off almost anything you want. It can be the photo of your pets, your favorite books, your favorite projects, or anything else you want to show to the world.
    </p>
    <p>
        You can create a new showcase item by creating a new file in the <code>_showcase</code> folder. It gives you the highest flexibility to customize the item using any HTML code.
    </p>
    <p>
        Cards are ordered by the <code>date</code> field in the front matter in descending order. The <code>width</code> field is used to determine the width of the card, ranging from 1 to 12.
        Layout is done by the <a href="https://masonry.desandro.com/" target="_blank">Masonry</a> library.
    </p>
    <p>
        For a tidy layout, it is recommended to set the width of the cards to be either multiple of 3 or multiple of 4 for all cards, except for small badges that do not take up much space (width=1).
    </p>
</div>

<div>
  <img data-src="https://api.star-history.com/svg?repos=luost26/academic-homepage&type=Date" class="lazy w-100 rounded-xl-top" src="{{ '/assets/images/empty_300x200.png' | relative_url }}">
  <div class="card-body">
    <h5 class="card-title">GitHub Star History</h5>
    <p class="card-text">
      This image shows the star history of the GitHub repository of this website.
    </p>
    <p class="card-text"><small><a href="https://github.com/luost26/academic-homepage" target="_blank">Give a star!</a></small></p>
  </div>
</div>
