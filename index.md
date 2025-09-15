{% assign header = site.header_image | default: "/assets/img/Homepage-cover.jpg" %}
<header class="masthead" style="background-image: url('{{ header | relative_url }}')">
  <div class="container position-relative px-4 px-lg-5">
    <div class="site-heading">
      <h1>{{ site.title }}</h1>
      <span class="subheading">{{ site.description }}</span>
    </div>
  </div>
</header>
