<template>
  <div class="container">
    <div class="card shadow-md">

      <div class="card-header">
        <div class="row">
          <div class="col">
            <h5
              class="mb-0 "
              data-toggle="collapse"
              href="#multiCollapseExample1"
              role="button"
              aria-expanded="false"
              aria-controls="multiCollapseExample1"
            >

              Collapsible Group Item #1

            </h5>

          </div>

        </div>
        <hr class="line" />

        <div>
          <div>
            <div
              class="collapse multi-collapse"
              id="multiCollapseExample1"
            >
              <div class="card-body">
                <!-- progress bar -->
                <div class="progress">
                  <div
                    class="progress-bar"
                    role="progressbar"
                    style="width: 25%;"
                    aria-valuenow="25"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
            </div>
          </div>

        </div>

      </div>
      <div class="card-header">
        <div class="row">
          <div class="col">
            <h5
              class="mb-0 "
              data-toggle="collapse"
              href="#multiCollapseExample2"
              role="button"
              aria-expanded="false"
              aria-controls="multiCollapseExample2"
            >

              Collapsible Group Item #2

            </h5>

          </div>

        </div>

        <div>
          <div>
            <div
              class="collapse multi-collapse"
              id="multiCollapseExample2"
            >
              <div class="card-body">
                <!-- progress bar -->
                <div class="progress">
                  <div
                    class="progress-bar"
                    role="progressbar"
                    style="width: 25%;"
                    aria-valuenow="25"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
            </div>
          </div>

        </div>

      </div>

    </div>

  </div>

</template>
