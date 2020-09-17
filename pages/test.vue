<template>
  <div class="container">
    <div class="selectContainer">
      <select
        name="mySelect"
        class="form-control pickerSelectClass"
        id="id_mySelect"
      ></select>

    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  mounted() {
    $(document).ready(function() {
      $(".pickerSelectClass").selectpicker();

      $("#id_mySelect").html(
        '<option value="0">[Nothing selected]</option>' +
          '<option value="1">Option 1</option>' +
          '<option value="2">Option 2</option>'
      );
      $("#id_mySelect").selectpicker("refresh");
    });
  }
};
</script>
<style scoped>
.selectContainer {
  width: 200px;
}

/* 1. Change color of the first option [Nothing selected] when select menu is closed? */
.bootstrap-select.btn-group
  .dropdown-toggle[title="[Nothing selected]"]
  .filter-option {
  color: red;
}

/* 2. Change color when there are chosen other select options when select menu is closed? */
.bootstrap-select.btn-group .dropdown-toggle .filter-option {
  color: blue;
}

/* 3. Change option's color when the select menu is opened? */
.bootstrap-select.btn-group .dropdown-menu > li > a {
  color: green;
}

/* 4. Change color when option on hover when select menu is opened? */
.bootstrap-select.btn-group .dropdown-menu > li > a:hover:not(:focus) {
  color: orange;
}

/* 5. Change background color of the whole select menu when is opened? */
.bootstrap-select.btn-group .dropdown-menu {
  background-color: yellow;
}
</style>
