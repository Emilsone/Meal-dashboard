<template>
  <main>
    <section>
      <div class="columns is-variable is-0">
        <div
          class="column is-10-desktop is-offset-2-desktop is-9-tablet is-offset-3-tablet is-12-mobile"
        >
          <div class="p-1">
            <div class="columns is-variable is-desktop">
              <div class="column">
                <h1 class="title">
                  Dashboard
                </h1>
              </div>
            </div>

            <div class="columns  is-variable is-desktop my-6">
              <div class="column">
                <div class="card has-background-primary has-text-white">
                  <!-- <div class="card-header"> -->
                  <div class="card-header-title has-text-white">
                    <h1>Confirm Meeting</h1>
                  </div>
                  <!-- </div> -->
                  <div class="card-content">
                    <p class="is-size-3">56,590</p>
                  </div>
                </div>
              </div>
              <div class="column">
                <div class="card has-background-warning has-text-black">
                  <!-- <div class="card-header"> -->
                  <div class="card-header-title has-text-black is-uppercase">
                    <h1>Enquiry Sent</h1>
                  </div>
                  <!-- </div> -->
                  <div class="card-content">
                    <p class="is-size-3">55%</p>
                  </div>
                </div>
              </div>
              <div class="column">
                <div class="card has-background-info has-text-white">
                  <!-- <div class="card-header"> -->
                  <div class="card-header-title has-text-white is-uppercase">
                    <h1>Unread Messages</h1>
                  </div>
                  <!-- </div> -->
                  <div class="card-content">
                    <p class="is-size-3">78 %</p>
                  </div>
                </div>
              </div>
              <div class="column">
                <div class="card has-background-info has-text-white">
                  <!-- <div class="card-header"> -->
                  <div class="card-header-title has-text-white is-uppercase">
                    <h1>Message</h1>
                  </div>
                  <!-- </div> -->
                  <div class="card-content">
                    <p class="is-size-3">78 %</p>
                  </div>
                </div>
              </div>
              <div class="column">
                <div class="card has-background-danger has-text-white">
                  <!-- <div class="card-header"> -->
                  <div class="card-header-title has-text-white">
                    Connections request
                  </div>
                  <!-- </div> -->
                  <div class="card-content">
                    <p class="is-size-3">425k</p>
                  </div>
                </div>
              </div>
            </div>

            <!-- second--------------------------------------------------------------------column -->
            <div class="columns  is-variable is-desktop">
              <div class="column">
                <div class="card has-background-primary has-text-white">
                  <!-- <div class="card-header"> -->
                  <div class="card-header-title has-text-white">
                    <h1>Connect and build with other events</h1>
                  </div>
                  <!-- </div> -->
                  <div class="card-content">
                    <p class="is-size-3">56,590</p>
                  </div>
                </div>
              </div>
              <div class="column">
                <div class="card has-background-warning has-text-black">
                  <!-- <div class="card-header"> -->
                  <div class="card-header-title has-text-black ">
                    <h1>Connect with exhibitors and start</h1>
                  </div>
                  <!-- </div> -->
                  <div class="card-content">
                    <p class="is-size-3">55%</p>
                  </div>
                </div>
              </div>
              <div class="column">
                <div class="card has-background-info has-text-white">
                  <!-- <div class="card-header"> -->
                  <div class="card-header-title has-text-white is-uppercase">
                    <h1>Exhibitors who view your profile</h1>
                  </div>
                  <!-- </div> -->
                  <div class="card-content">
                    <p class="is-size-3">78 %</p>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- third-card -->
          <div class="columns  is-variable is-desktop">
            <!-- <div class="columns"> -->
              <div class="column is-two-thirds">
                <div class="card-content" id="contentapp">
                  <div
                    class="card"
                    id="first-card"
                    
                  >
                    <span>
                      <i
                        class="fa fa-money"
                        aria-hidden="true"
                        style="color"
                      ></i>
                    </span>
                    <p class="subtitle p-6">
                      Jeff Atwood
                    </p>
                  </div>
                </div>
              </div>

              <div class="column">
                <div class="card has-background-light has-text-black ">
                  <!-- <div class="card-header"> -->
                  <div class="card-header-title has-text-black">
                    <h1>Event Update & Feed</h1>
                  </div>
                    <img src="../assets/event.png" alt="event image " class="event-image ml-6">
                  <div class="card-content">
                    <p class="">No Records Available </p>
                  </div>
                </div>
              </div>
            <!-- </div> -->
          </div>

          <div class="columns  is-variable is-desktop">
            <!-- <div class="columns"> -->
              <div class="column is-two-thirds">
                <div class="card-content" id="contentapp">
                  <div
                    class="card"
                    id="first-card"
                    
                  >
                    <span>
                      <i
                        class="fa fa-money"
                        aria-hidden="true"
                        style="color"
                      ></i>
                    </span>
                    <p class="subtitle p-6">
                      Jeff Atwood
                    </p>
                  </div>
                </div>
              </div>

              <div class="column">
                <div class="card has-background-primary has-text-white ">
                 
                  <div class="card-content">
                    <h1 class="has-text-centered">Welcome to the help center</h1>
                    <p class="has-text-centered">Explore all advanced features to get maximum buyer engagement </p>
                  </div>
                </div>
              </div>
            <!-- </div> -->
          </div>
        </div>
      </div>
    </section>
  </main>
</template>
<script>
export default {
  name: "Main",
};
</script>
<style scoped>
.event-image{
  width: 80%;
  height: 80%;
}
</style>
