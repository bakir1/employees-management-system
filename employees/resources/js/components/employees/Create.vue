<template>
  <div>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-8">
          <div class="card">
            <div class="card-header">
              Create Employees
              <router-link :to="{ name: 'EmployeesIndex' }" class="float-right"
                >Back</router-link
              >
            </div>

            <div class="card-body">
              <form>
                <div class="form-group row">
                  <label
                    for="country_code"
                    class="col-md-4 col-form-label text-md-right"
                    >Country</label
                  >

                  <div class="col-md-6">
                    <select
                      name="country_id"
                      class="form-control"
                      aria-label="Default select example"
                    >
                      <option selected>Open this select menu</option>
                    </select>
                  </div>
                </div>

                <div class="form-group row">
                  <label
                    for="first_name"
                    class="col-md-4 col-form-label text-md-right"
                    >First Name</label
                  >

                  <div class="col-md-6">
                    <input
                      id="first_name"
                      type="text"
                      class="form-control"
                      required
                    />
                  </div>
                </div>

                <div class="form-group row">
                  <label
                    for="middle_name"
                    class="col-md-4 col-form-label text-md-right"
                    >Middle Name</label
                  >

                  <div class="col-md-6">
                    <input
                      id="middle_name"
                      type="text"
                      class="form-control"
                      required
                    />
                  </div>
                </div>

                 <div class="form-group row">
                  <label
                    for="last_name"
                    class="col-md-4 col-form-label text-md-right"
                    >Last Name</label
                  >

                  <div class="col-md-6">
                    <input
                      id="last_name"
                      type="text"
                      class="form-control"
                      required
                    />
                  </div>
                </div>

                 <div class="form-group row">
                  <label
                    for="address"
                    class="col-md-4 col-form-label text-md-right"
                    >Address</label
                  >

                  <div class="col-md-6">
                    <input
                      id="address"
                      type="text"
                      class="form-control"
                      required
                    />
                  </div>
                </div>

                 <div class="form-group row">
                  <label
                    for="zip_code"
                    class="col-md-4 col-form-label text-md-right"
                    >Zip Code</label
                  >

                  <div class="col-md-6">
                    <input
                      id="zip_code"
                      type="text"
                      class="form-control"
                      required
                    />
                  </div>
                </div>




                <div class="form-group row mb-0">
                  <div class="col-md-6 offset-md-4">
                    <button type="submit" class="btn btn-primary">Store</button>
                  </div>
                </div>
              </form>
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

<style>
</style>