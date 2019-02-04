<section class="nes-container t-grey with-title">
  <h2 class="title tred">Participants</h2>
  <table class="nes-table is-bordered is-centered">
      <thead>
          <th>Name</th>
          <th>Company</th>
          <th>Role</th>
          <th>Contact</th>
      </thead>
      <tbody>
    {% for page in site.pages %}
      {% if page.resource == true %}
        {% for pc in page.categories %}
          {% if pc == "whoami" %}
              <tr>
                  <td><a href="/tamedia-hackdays{{ page.url }}">{{ page.yourname }}</a></td>
                  <td>{{ page.company }}</td>
                  <td>{{ page.role }}</td>
                  <td>{{ page.contact | markdownify }}</td>
              </tr>
          {% endif %}   <!-- cat-match-p -->
        {% endfor %}  <!-- page-category -->
      {% endif %}   <!-- resource-p -->
    {% endfor %}  <!-- page -->
      </tbody>
  </table>
</section>

<i class="nes-charmander"></i>

<section class="nes-container t-grey with-title">
  <h2 class="title tred">Hints for Adding Yourself to this List</h2>

  <ul class="nes-list is-disc">
    <li>Put your character sheet in the /tamedia-hackdays/whoami/ directory of this git repository</li>
    <li>You can use <a href="/tamedia-hackdays/whoami/harryfuecks">this page</a> as a template. Make sure to use the meta tags at the top of the file (see template for clues)</li>
    <li>If you want a Gameboy-ified version of your photo <a href="http://yrlab.zatunen.com/webgl/gbpic/gbpic.html">try this</a> (Google Translate FTW)</li>
    <li>Put your pictures in the /tamedia-hackdays/whoami/pics/ directory of this repo</li>
  </ul>
</section>