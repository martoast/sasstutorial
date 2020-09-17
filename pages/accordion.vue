<template>
  <div>
    <div class="container">
      <div class="accordion-group accordion-caret">
        <div class="accordion-heading">
          <a
            class="collapse-toggle"
            data-toggle="collapse"
            href="#collapseOne"
          >
            <strong>Header</strong>
          </a>
        </div>
        <div
          id="collapseOne"
          class="collapse show"
        >
          <div
            class="accordion-inner"
            id="collapseOne"
            aria-labelledby="headingOne"
            data-parent="#accordionExample"
          >
            <!-- LIST TABLE INJECTED HERE -->
            <div class="container">
              <table class="table table-hover">
                <thead class="text-light-gray">
                  <tr>
                    <th scope="col"></th>
                    <th scope="col">First</th>
                    <th scope="col">Last</th>
                    <th scope="col">Handle</th>
                  </tr>
                </thead>
                <tbody>
                  <tr class="table tr">
                    <td>Mark</td>
                    <td>Mark</td>
                    <td>Otto</td>
                    <td>@mdo</td>
                  </tr>
                  <tr>
                    <td>Mark</td>
                    <td>Jacob</td>
                    <td>Thornton</td>
                    <td>@fat</td>
                  </tr>
                  <tr>
                    <td>Mark</td>
                    <td>Alex</td>
                    <td>Martos</td>
                    <td>@fatty</td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
      </div>

    </div>

  </div>

</template>
<style scoped>
.accordion-caret .accordion-toggle:hover {
  text-decoration: none;
  color: blueviolet;
}
.accordion-caret .accordion-toggle:hover span,
.accordion-caret .accordion-toggle:hover strong {
  text-decoration: underline;
}
.accordion-caret .accordion-toggle:before {
  font-size: 25px;

  vertical-align: -3px;
}
</style>
