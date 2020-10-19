<template>
  <header>
    <nav class="navbar is-fixed-top box-shadow-y" id="navbar">
      <div class="navbar-brand">
        <a
          role="button"
          class="navbar-burger toggler"
          aria-label="menu"
          aria-expanded="false"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>

        <a href="#" class="navbar-item has-text-weight-bold has-text-black">
          Kitchen
          <span class="icon is-small pl-5">
            <i class="fas fa-globe"></i>
          </span>
        </a>
        <a
          role="button"
          class="navbar-burger nav-toggler"
          aria-label="menu"
          aria-expanded="false"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>
      <div class="navbar-menu has-background-white">
        <div class="field  my-2 ml-6">
          <p class="control has-icons-left">
            <span class="select">
              <select>
                <option selected>Select Event</option>
                <option>Select dropdown</option>
                <option>With options</option>
              </select>
            </span>
            <!-- <span class="icon is-small is-left">
             <i class="fas fa-calendar-check-o" aria-hidden="true"></i>

            </span> -->
          </p>
        </div>
        <div class="navbar-end p-6">
          <a href="#" class="navbar-item">
            <span><i class="fa fa-bell" aria-hidden="true"></i> </span>
          </a>

          <a href="#" class="navbar-item">
            <span><i class="fa fa-envelope" aria-hidden="true"></i> </span>
          </a>

          <div class="navbar-item has-dropdown is-hoverable">
            <img src="../assets/user-1.png" alt="a user icon" class="mt-4" />
            <a href="#" class="navbar-link">
              John
            </a>
            <div class="navbar-dropdown is-right">
              <a href="#" class="navbar-item">
                Profile
              </a>
              <a href="#" class="navbar-item">Settings</a>
              <hr class="navbar-divider" />
              <a href="#" class="navbar-item">Log Out</a>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <div class="columns is-variable is-0">
      <div class="menu-container px-1 has-background-white">
        <div class="menu-wrapper py-1">
          <aside class="menu">
            <p class="menu-label has-text-lighter">Kitchen</p>
            <ul class="menu-list">
              <li class="dashboard py-2 ">
                <a href="#" class="has-text-black">
                  <i class="fa fa-th icon" aria-hidden="true"></i>

                  Dashboard</a
                >
              </li>
            </ul>
            <ul class="menu-list">
              <li>
                <a href="#" class="has-text-black">
                  <i class="fa fa-cutlery icon" aria-hidden="true"></i>
                  Products</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fa fa-address-book-o icon" aria-hidden="true"></i>
                  Exhibitors</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fa fa-tint icon" aria-hidden="true"></i>
                  Exhibitions</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fa fa-gift icon" aria-hidden="true"></i>
                  Invitations</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fa fa-question icon" aria-hidden="true"></i>
                  RFQ</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fa fa-user icon" aria-hidden="true"></i>

                  My Profile</a
                >
              </li>
            </ul>

            <div class="column">
              <div class="card has-text-black" id="digital-card">
                <div class="card-header">
                  <div
                    class="card-header-title has-text-black "
                    id="card-header"
                  >
                    <i class="fa fa-bookmark icon" aria-hidden="true"></i>
                    <h1 class="has-text-white">Access Events</h1>
                  </div>
                </div>
                <div class="card-content">
                  <p class="is-size-">
                    click <i class="fa fa-bookmark" aria-hidden="true"></i>
                    to view digital events
                  </p>
                </div>
              </div>
            </div>
          </aside>
        </div>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  name: "Nav",
};
</script>
<style scoped>
.fa-bookmark {
  background-color: white;
  padding: 20px 20px;
  border-radius: 5px;
}
#card-header {
  background-color: #416ff8;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
#digital-card {
  border-radius: 20px;
  padding: 20px;
   background-color: #f1f6ff;
}
.feild {
  margin: auto;
}
.control {
  text-align: center;
}
.dashboard {
  background-color: #d8ddee;
}
.navbar-menu{
   background-color: #f1f6ff;
}
</style>
