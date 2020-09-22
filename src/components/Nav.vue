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
          Admin Dashboard
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
        <div class="navbar-start">
          <a href="#" class="navbar-item">
            <i class="fas fa-home icon"></i> Home
          </a>
          <a href="#" class="navbar-item">
            About
          </a>
          <a href="#" class="navbar-item">
            Features
          </a>
          <a href="#" class="navbar-item">Pricing</a>
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
            <p class="menu-label has-text-lighter">General</p>
            <ul class="menu-list">
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-tachometer-alt icon"></i>
                  Dashboard</a
                >
              </li>
            </ul>
            <p class="menu-label has-text-lighter">Administration</p>
            <ul class="menu-list">
              <li>
                <a href="#" class="is-active has-background-primary">
                  <i class="fas fa-cogs icon"></i>
                  Settings</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-users-cog icon"></i>
                  Manage Team</a
                >
                <ul>
                  <li>
                    <a href="#" class="has-text-black">
                      <i class="fas fa-users icon"></i>
                      Members</a
                    >
                  </li>
                  <li>
                    <a href="#" class="has-text-black">
                      <i class="fas fa-user-plus icon"></i>
                      Add New</a
                    >
                  </li>
                </ul>
              </li>
            </ul>
            <p class="menu-label has-text-lighter">Other</p>
            <ul class="menu-list">
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-comments icon"></i>
                  Chats</a
                >
              </li>
              <li>
                <a href="#" class="has-text-black">
                  <i class="fas fa-info-circle icon"></i>
                  Extras</a
                >
              </li>
            </ul>
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

</style>
