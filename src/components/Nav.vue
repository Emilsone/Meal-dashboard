<template>
  <header>
    <nav class="navbar is-fixed-top box-shadow-y">
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
        <div class="field my-2 ml-6">
          <p class="control has-icons-left">
            <span class="select">
              <select>
                <option selected>Select Event</option>
                <option>Select dropdown</option>
                <option>With options</option>
              </select>
            </span>
            <span class="icon is-small is-left">
              <i class="fas fa-globe"></i>
            </span>
          </p>
        </div>
        <div class="navbar-end">
          <a href="#" class="navbar-item">
            Notifications
          </a>
          <div class="navbar-item has-dropdown is-hoverable">
            <a href="#" class="navbar-link">
              Admin
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
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-tachometer-alt icon"></i>
                  Dashboard</a
                >
              </li>
            </ul>
            <ul class="menu-list">
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-comments icon"></i>
                  Products</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-info-circle icon"></i>
                  Exhibitions</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-info-circle icon"></i>
                  Exhibitors</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-info-circle icon"></i>
                  Invitations</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-info-circle icon"></i>
                  RFQ</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-info-circle icon"></i>
                  My Profile</a
                >
              </li>
            </ul>

            <div class="column">
              <div class="card has-background-warning has-text-black">
                <div class="card-header">
                  <div
                    class="card-header-title has-text-black is-uppercase"
                    id="card-header"
                  >
                    <a href="#" class="has-text-black">
                      <i class="fas fa-bookmark icon"></i>
                      Access Events
                    </a>
                  </div>
                </div>
                <div class="card-content">
                  <p class="is-size-">click to view digital events</p>
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
  padding: 20px 30px;
  border-radius: 5px;
}
#card-header {
  background-color: rgb(70, 78, 197);
}
</style>
