---
show: true
width: 4
date: 2024-01-12 00:01:00 +0800

height: 400px
images:

- src: assets/images/photos/paris/Paris3.jpg
  title: Tour Eiffel
  desc: 埃菲尔铁塔
- src: assets/images/photos/paris/Paris2.jpg
  title: Arc de triomphe de l'Étoile
  desc: 凯旋门
- src: assets/images/photos/paris/Paris4.jpg
  title: Magical Street Scenery
  desc: 神奇的街边景色
- src: assets/images/photos/paris/Paris1.jpg
  title: Chat with LeCun
  desc: ICCV 会场偶遇 LeCun
#   link: https://picsum.photos/

---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}

<div class="p-4">
    <h2>Paris</h2>
    <!-- <hr />
    <p>
        <code>Showcase</code> is a page where you can show off almost anything you want. It can be the photo of your pets, your favorite books, your favorite projects, or anything else you want to show to the world.
    </p> -->
</div>
