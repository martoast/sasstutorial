<template>
  <div class="container">

    <div>
      <h1>Components Breakdown</h1>
    </div>
    <div class="container">

      <div>
        <button
          type="button"
          class="btn btn-info btn-round shadow-lg"
        >
          <span class="btn-dot"></span>
        </button>

        <button
          type="button"
          class="btn btn-primary btn-round"
        >
          <span class="btn-dot"></span>
        </button>

      </div>

      <!-- GREEN ROUND BUTTONS  -->
      <div>
        <button class="btn btn-success btn-round">
          JH
        </button>
      </div>
      <div>
        <button class="btn btn-success btn-round text-white">
          JH
        </button>
      </div>
      <!-- BLOCK BUTTON -->
      <div>
        <button class="btn btn-success">
          New Deals
        </button>
      </div>
    </div>
    <!-- SEARCH BAR -->
    <div class="mb-3">
      <form>
        <div class="input-group">
          <input
            type="text"
            class="form-control"
            placeholder="Search by Client"
          />
          <div class="input-group-btn">
            <button
              class="btn btn-default"
              type="submit"
            >
              <i class="glyphicon glyphicon-search"></i>
            </button>
          </div>
        </div>
      </form>
    </div>
    <!-- progress bar -->
    <div class="progress mb-3">
      <div
        class="progress-bar"
        role="progressbar"
        style="width: 25%;"
        aria-valuenow="25"
        aria-valuemin="0"
        aria-valuemax="100"
      >
        25%
      </div>
    </div>
    <!-- tabs -->
    <div class="container">
      <div>
        <h1>tabs</h1>
      </div>
      <div class="tab-card shadow-sm">
        <div class="card-header">
          <ul
            class="nav nav-pills"
            id="myTab"
            role="tablist"
          >
            <li
              class="nav-item"
              role="presentation"
            >
              <a
                class="nav-link active"
                id="home-tab"
                data-toggle="tab"
                href="#home"
                role="tab"
                aria-controls="home"
                aria-selected="true"
              >Home</a>
            </li>
            <li
              class="nav-item"
              role="presentation"
            >
              <a
                class="nav-link"
                id="profile-tab"
                data-toggle="tab"
                href="#profile"
                role="tab"
                aria-controls="profile"
                aria-selected="false"
              >Profile</a>
            </li>
            <li
              class="nav-item"
              role="presentation"
            >
              <a
                class="nav-link"
                id="contact-tab"
                data-toggle="tab"
                href="#contact"
                role="tab"
                aria-controls="contact"
                aria-selected="false"
              >Contact</a>
            </li>
          </ul>
        </div>

        <div class="card-body">
          <div
            class="tab-content"
            id="myTabContent"
          >
            <div
              class="tab-pane fade show active"
              id="home"
              role="tabpanel"
              aria-labelledby="home-tab"
            >
              "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
              ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
              aliquip ex ea commodo consequat. Duis aute irure dolor in
              reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
              pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
              culpa qui officia deserunt mollit anim id est laborum."
            </div>
            <div
              class="tab-pane fade"
              id="profile"
              role="tabpanel"
              aria-labelledby="profile-tab"
            >
              "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
              ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
              aliquip ex ea commodo consequat. Duis aute irure dolor in."
            </div>
            <div
              class="tab-pane fade"
              id="contact"
              role="tabpanel"
              aria-labelledby="contact-tab"
            >
              "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua."
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="accordion-group accordion-caret">
      <div class="accordion-heading">
        <a
          class="accordion-toggle"
          data-toggle="collapse"
          href="#collapseOne"
        >
          <strong>Header</strong>
        </a>
      </div>
      <div
        id="collapseOne"
        class="accordion-body collapse in"
      >
        <div
          class="accordion-inner"
          id="collapseOne"
          aria-labelledby="headingOne"
          data-parent="#accordionExample"
        >
          <div>
            <div class="card-body">
              Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus
              terry richardson ad squid. 3 wolf moon officia aute, non cupidatat
              skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod.
              Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid
              single-origin coffee nulla assumenda shoreditch et. Nihil anim
              keffiyeh helvetica, craft beer labore wes anderson cred nesciunt
              sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings
              occaecat craft beer farm-to-table, raw denim aesthetic synth
              nesciunt you probably haven't heard of them accusamus labore
              sustainable VHS.
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.accordion-caret .accordion-toggle:hover {
  text-decoration: none;
}
.accordion-caret .accordion-toggle:hover span,
.accordion-caret .accordion-toggle:hover strong {
  text-decoration: underline;
}
.accordion-caret .accordion-toggle:before {
  font-size: 25px;
  vertical-align: -3px;
}
.accordion-caret .accordion-toggle:not(.collapsed):before {
  content: "▾";
  margin-right: 10px;
}
.accordion-caret .accordion-toggle.collapsed:before {
  content: "▸";
  margin-right: 10px;
}
</style>
