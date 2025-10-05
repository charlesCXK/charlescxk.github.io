---
show: true
width: 4
date: 2024-01-12 00:01:00 +0800

height: 400px
images:

- src: assets/images/photos/cat/cat1.jpg
  title: Warming itself on the radiator
  desc: 小猫在暖气片上取暖
- src: assets/images/photos/cat/cat2.jpg
  title: Eye contact
  desc: 对视
- src: assets/images/photos/cat/cat3.jpg
  title: With her fish friend
  desc: 小猫和🐟朋友
- src: assets/images/photos/cat/cat4.jpg
  title: Showing off her long legs
  desc: 展示大长腿
#   link: https://picsum.photos/

---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}

<div class="p-4">
    <h2>Cat (橙子)</h2>
    <!-- <hr />
    <p>
        <code>Showcase</code> is a page where you can show off almost anything you want. It can be the photo of your pets, your favorite books, your favorite projects, or anything else you want to show to the world.
    </p> -->
</div>
