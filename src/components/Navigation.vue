<template>
  <nav class="navigation">
    <img
      class="navigation__menu_logo"
      src="@/assets/menu.png"
      alt="navigation menu mobile"
    />
    <img class="navigation__logo" src="@/assets/logo.png" alt="logo" />
    <ul class="navigation__menu">
      <li class="navigation__menu-item navigation__menu-item--active">
        Despre
      </li>
      <li class="navigation__menu-item">Finantari</li>
      <li class="navigation__menu-item">Stiri</li>
      <li class="navigation__menu-item">Aplicatii</li>
      <li class="navigation__menu-item">Consultanta</li>
      <li class="navigation__menu-item">Marketplace</li>
      <li class="navigation__menu-item">Joburi</li>
      <li class="navigation__menu-item">Comunicare</li>
      <li class="navigation__menu-item">Anunturi</li>
    </ul>
    <div class="navigation__profile">
      <div class="navigation__profile-nots">
        <img src="@/assets/bell.png" alt="bell" />
        <div class="navigation__profile-nots-number">
          <p>4</p>
        </div>
      </div>
      <div class="navigation__profile-welcome">
        Salut, <span>Alexandru!</span>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style>
.navigation {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 30px;
}

.navigation__menu {
  list-style-type: none;
  display: flex;
}

.navigation__menu_logo {
  display: none;
}

.navigation__menu-item {
  margin-right: 40px;
  color: #dddde7;
  font-size: 25px;
  font-weight: 300;
  cursor: pointer;
}

.navigation__menu-item--active {
  color: white;
  font-weight: bold;
}

.navigation__profile {
  display: flex;
}

.navigation__profile-nots {
  display: flex;
  align-items: center;
  position: relative;
  margin-right: 25px;
  cursor: pointer;
}

.navigation__profile-nots-number {
  position: absolute;
  top: 0;
  right: -14px;
  width: 16px;
  height: 16px;
  border-radius: 50%;
  background-color: #38bfaa;
  display: flex;
  justify-content: center;
  align-items: center;
}

.navigation__profile-nots-number p {
  color: white;
  font-size: 16px;
  margin-top: 2px;
}

.navigation__profile-welcome {
  background-image: linear-gradient(#5381a4, #10cc7a);
  font-size: 25px;
  border-radius: 6px;
  padding-left: 10px;
  padding-right: 10px;
  color: white;
  font-weight: 300;
  cursor: pointer;
}

.navigation__profile-welcome span {
  font-weight: bold;
}

@media screen and (max-width: 1330px) {
  .navigation__menu-item {
    margin-right: 25px;
  }
}

@media screen and (max-width: 1150px) {
  .navigation__menu {
    display: none;
  }

  .navigation__menu_logo {
    display: block;
    width: 40px;
    height: auto;
  }
}
</style>