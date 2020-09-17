<template>
  <div class="container">
    <!-- DROP DOWNS -->
    <div>
      <h1>Dropdowns</h1>
    </div>
    <div>
      <select
        class="custom-select dropdown-outline-success"
        id="inputGroupSelect01"
      >
        <option selected>All</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
    </div>
    <!-- <div>
      <div class="btn btn-primary">
        hey
      </div>
    </div> -->

    <!-- dropdown using forms -->
    <div class="mt-4">
      <form class="form-inline">
        <div class="form-group">
          <select
            class="custom-select-outline-secondary"
            id="exampleFormControlSelect1"
          >
            <option>Not started yet</option>
            <option>2</option>
            <option>3</option>

          </select>
        </div>
        <div class="form-group ml-2">
          <select
            class="form-control-sm custom-select-outline-success"
            id="exampleFormControlSelect1"
          >
            <option>In progress</option>
            <option>2</option>
            <option>3</option>
            <option>4</option>
            <option>5</option>
          </select>
        </div>
        <div class="form-group ml-2">
          <select
            class="form-control custom-select-outline-info"
            id="exampleFormControlSelect1"
          >
            <option>In progress</option>
            <option>2</option>
            <option>3</option>
            <option>4</option>
            <option>5</option>
          </select>
        </div>
      </form>
    </div>
  </div>
</template>
