---
layout: home
lang-ref: page-home
landing: true
---
<!-- Main -->
<article id="main">

    <!-- Three -->
    <section class="wrapper style3 container special">

        <header class="major">
            <h2>Senaste <strong>artiklarna</strong></h2>
        </header>

        {%- assign posts = paginator.posts | default: site.posts -%}
		{% include post_grid.html posts=posts limit=4 %}

        <footer class="major">
            <ul class="buttons">
                <li><a href="/artiklar" class="button">Fler</a></li>
            </ul>
        </footer>

    </section>

</article>