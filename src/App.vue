<template>
 <div class="container py-5">
      <div class="row d-flex justify-content-center align-items-center">
        <div class="col-10">
          <div class="card rounded">
            <div class="card-body p-5">
              <!-- Title -->
              <h3 class="mb-3 fw-bold">
                Todo List
                <span class="badge bg-primary rounded-pill ms-3 fs-6 fw-normal">
                  5 task
                </span>
              </h3>

              <!-- Form input -->
              <form class="row align-items-center mb-3 gy-2">
                <div class="col-sm-12 col-md-10">
                  <div class="form-floating">
                    <input
                      type="text"
                      class="form-control fs-4"
                      id="floatingInput"
                      placeholder="Todos"
                      autocomplete="off"
                    />
                    <label for="floatingInput">What's your plan today</label>
                  </div>
                </div>
                <div class="col-sm-12 col-md-2">
                  <div class="d-grid">
                    <button
                      type="submit"
                      class="btn btn-primary btn-lg"
                      disabled
                    >
                      <i class="fa fa-plus-circle me-2" aria-hidden="true"></i
                      >ADD
                    </button>
                  </div>
                </div>
              </form>

              <!-- Todo list -->
              <ul class="list-group list-group-flush">
                <!-- list 1 -->
                <li class="list-group-item">
                  <div class="row gy-2">
                    <div
                      class="col-sm-12 col-md-auto me-auto align-self-center fs-5"
                    >
                      Learn Pinia state management
                    </div>
                    <div class="col-sm-12 col-md-auto">
                      <div class="row gx-2">
                        <div class="col-auto">
                          <button class="btn btn-outline-success">
                            <i
                              class="fa fa-check-circle"
                              aria-hidden="true"
                            ></i>
                          </button>
                        </div>
                        <div class="col-auto">
                          <button class="btn btn-outline-danger">
                            <i class="fa fa-eraser" aria-hidden="true"></i>
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
                <!-- list 2 -->
                <li class="list-group-item">
                  <div class="row gy-2">
                    <div
                      class="col-sm-12 col-md-auto me-auto align-self-center fs-5 text-decoration-line-through text-muted"
                    >
                      Learn authentication firebase
                    </div>
                    <div class="col-sm-12 col-md-auto">
                      <div class="row gx-2">
                        <div class="col-auto">
                          <button class="btn btn-outline-secondary">
                            <i
                              class="fa fa-check-circle"
                              aria-hidden="true"
                            ></i>
                          </button>
                        </div>
                        <div class="col-auto">
                          <button class="btn btn-outline-secondary">
                            <i class="fa fa-eraser" aria-hidden="true"></i>
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
                <!-- list 3 -->
                <li class="list-group-item">
                  <div class="row gy-2">
                    <div
                      class="col-sm-12 col-md-auto me-auto align-self-center fs-5"
                    >
                      Learn composition API
                    </div>
                    <div class="col-sm-12 col-md-auto">
                      <div class="row gx-2">
                        <div class="col-auto">
                          <button class="btn btn-outline-success">
                            <i
                              class="fa fa-check-circle"
                              aria-hidden="true"
                            ></i>
                          </button>
                        </div>
                        <div class="col-auto">
                          <button class="btn btn-outline-danger">
                            <i class="fa fa-eraser" aria-hidden="true"></i>
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
                <!-- list 4 -->
                <li class="list-group-item">
                  <div class="row gy-2">
                    <div
                      class="col-sm-12 col-md-auto me-auto align-self-center fs-5"
                    >
                      Learn vite features
                    </div>
                    <div class="col-sm-12 col-md-auto">
                      <div class="row gx-2">
                        <div class="col-auto">
                          <button class="btn btn-outline-success">
                            <i
                              class="fa fa-check-circle"
                              aria-hidden="true"
                            ></i>
                          </button>
                        </div>
                        <div class="col-auto">
                          <button class="btn btn-outline-danger">
                            <i class="fa fa-eraser" aria-hidden="true"></i>
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
                <!-- list 5 -->
                <li class="list-group-item">
                  <div class="row gy-2">
                    <div
                      class="col-sm-12 col-md-auto me-auto align-self-center fs-5"
                    >
                      Create documentation auth firebase on Youtube channel
                    </div>
                    <div class="col-sm-12 col-md-auto">
                      <div class="row gx-2">
                        <div class="col-auto">
                          <button class="btn btn-outline-success">
                            <i
                              class="fa fa-check-circle"
                              aria-hidden="true"
                            ></i>
                          </button>
                        </div>
                        <div class="col-auto">
                          <button class="btn btn-outline-danger">
                            <i class="fa fa-eraser" aria-hidden="true"></i>
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

</template>

<style>
@import './assets/base.css';



</style>
