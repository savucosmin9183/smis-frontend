<template>
  <div class="content">
    <div class="content__header">
      <ul class="content__header-menu">
        <li class="content__header-menu-item content__header-menu-item--active">
          Setari SmisApp
        </li>
        <li class="content__header-menu-item">Serviciile tale</li>
        <li class="content__header-menu-item">Adauga servicii</li>
        <li class="content__header-menu-item">Setari cont</li>
        <li class="content__header-menu-item">Companiile mele</li>
        <li class="content__header-menu-item">Financiar</li>
      </ul>
      <div class="content__menu-icons">
        <div class="content__menu-icons-icon"></div>
        <div class="content__menu-icons-icon"></div>
        <div class="content__menu-icons-icon"></div>
        <div class="content__menu-icons-icon"></div>
      </div>
    </div>
    <div class="content__container">
      <div class="block_presentation block1">
        <p class="block_presentation__title">Despre <span>Smis</span>App</p>
        <p class="block_presentation__subtitle">
          Prezentarea functiilor aplicatiei si optiunile de achizitie
        </p>
        <div class="block_presentation__row">
          <p class="block_presentation__row-title">Descrierea aplicatiei</p>
          <div class="block_presentation__row-content block1-description">
            SmisApp este tot universul Smis. Este aplicatia din care iti poti
            gestiona setarile contului, companiile adaugate, serviciile tale
            Smis precum si zona de financiar. SmisApp este disponibila în mod
            gratuit utilizatorilor Smis si nu necesita plata unui abonament.
            SmisApp este adaugata automat la contul tau odata cu crearea
            acestuia. Varianta cu licenta a aplicatiei permite mai multe actiuni
            si instalarea aplicatiei pentru mobil.
          </div>
        </div>
        <div class="block_presentation__row">
          <p class="block_presentation__row-title">Licenta de utilizare</p>
          <div
            class="
              block_presentation__row-content
              block_presentation__row-content-highlight
            "
          ></div>
        </div>
        <div class="block_presentation__row">
          <p class="block_presentation__row-title">Tip utilizatori</p>
          <div class="block_presentation__row-content width-auto">
            Toti utilizatorii inregistrati Smis
          </div>
        </div>
        <div class="block_presentation__row">
          <p class="block_presentation__row-title">Feedback-ul tau</p>
          <div class="block_presentation__row-content flex-column">
            <img
              class="block_presentation__stars"
              src="@/assets/stars.png"
              alt="rating"
            />
            <p class="opacity-font">Scrie un review! Iti multumim!</p>
          </div>
        </div>
      </div>
      <div class="block_presentation block2">
        <p class="block_presentation__title">Feedback</p>
        <p class="block_presentation__subtitle">
          Care este parerea utilizatorilor
        </p>
        <div class="block_presentation__row">
          <div>
            <div class="block_presentation__row-rating">
              <span>4.98</span> /5
              <img class="stars" src="@/assets/stars.png" alt="rating" />
            </div>
            <p class="block_presentation__rating-subtitle">
              Bazat pe 7.653 de review-uri
            </p>
          </div>
        </div>
        <div class="block_presentation__row statistics_row">
          <img src="@/assets/numbers.png" alt="numbers" />
          <img src="@/assets/graph.png" alt="numbers" />
          <img src="@/assets/numbers2.png" alt="numbers" />
        </div>
        <div class="block_presentation__row block_presentation_center">
          <p>Vezi prezentarea completa</p>
        </div>
      </div>
      <div class="block3">
        <div class="block_presentation">
          <p class="block_presentation__title">Utilizatori</p>
          <p class="block_presentation__subtitle">
            Numarul total de utilizatori SmisApp
          </p>
          <div class="block_presentation__row number_of_users">7.653</div>
        </div>
        <div class="block_presentation last_days-block">
          <img class="people_image" src="@/assets/people.png" alt="people" />
          <div class="last_days-block__text">
            <p>Ultimele 30 de zile</p>
            <div class="flex-row">
              672
              <img src="@/assets/uparrow.png" alt="arrow" />
            </div>
          </div>
        </div>
        <div class="block_presentation help-block">
          <p class="help_title">Ai nevoie de ajutor?</p>
          <p class="help_subtitle">Contacteaza un expert Smis</p>
          <img src="@/assets/smischat.png" alt="smis" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.content {
}

.content__header {
  display: flex;
  justify-content: space-between;
  padding: 10px 30px;
  background-color: white;
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
}

.content__header-menu {
  display: flex;

  align-items: center;
  list-style-type: none;
}

.content__header-menu-item {
  font-size: 22px;
  color: #c5ccd2;
  margin-right: 30px;
  cursor: pointer;
}

.content__header-menu-item--active {
  color: #5d6a83;
}

.content__menu-icons {
  display: flex;
}

.flex-row {
  display: flex;
  color: #10cc7a;
  font-size: 35px;
  margin-top: -20px;
}

.flex-row img {
  object-fit: contain;
  margin-top: -5px;
}

.content__menu-icons-icon {
  height: 40px;
  width: 40px;
  border-radius: 10px;
  margin-right: 10px;
  background-color: #c5ccd2;
  cursor: pointer;
  position: relative;
}

.content__menu-icons-icon:last-of-type {
  margin-right: 0;
  text-decoration-line: underline;
  text-decoration-style: solid;
}

.content__menu-icons-icon:last-of-type::after {
  content: "";
  width: 100%;
  height: 7px;
  border-radius: 10px;
  background-color: #c5ccd2;
  position: absolute;
  left: 0;
  bottom: -10px;
}

.content__container {
  background-color: #f0f5f8;
  padding: 30px;
  display: flex;
}

.block_presentation {
  background-color: white;
  border-radius: 15px;
  padding-top: 15px;
  color: #5d6a83;
}

.block1 {
  width: 46%;
  margin-right: 2%;
}

.block2 {
  width: 22%;
  margin-right: 2%;
}

.block3 {
  width: 22%;
}

.block_presentation__title {
  font-size: 45px;
  margin-left: 30px;
}

.block_presentation__title span {
  font-weight: 800;
}

.block_presentation__subtitle {
  color: #c5ccd2;
  font-size: 20px;
  margin-top: -20px;
  margin-bottom: 30px;
  margin-left: 30px;
}

.block_presentation__rating-subtitle {
  color: #c5ccd2;
  font-size: 20px;
  margin-top: -10px;
}

.block_presentation__row {
  padding: 20px 30px;
  border-bottom: 1px solid #c5ccd2;
  display: flex;
  justify-content: space-between;
}

.block_presentation__row:first-of-type {
  border-top: 1px solid #c5ccd2;
  border-bottom: 1px solid #c5ccd2;
}

.number_of_users {
  border-top: 1px solid #c5ccd2 !important;
  font-size: 60px;
  color: #60686e;
}

.block_presentation__row:last-of-type {
  border-top: none;
  border-bottom: none;
}

.block_presentation__row-title {
  font-size: 25px;
}

.block_presentation__row-content {
  width: 65%;
  margin-top: 5px;
  font-size: 18px;
  display: flex;
  justify-content: space-between;
}

.block_presentation__row-content-highlight {
  height: 30px;
  border-radius: 5px;
  border: 1px solid #c5ccd2;
}

.opacity-font {
  opacity: 0.7;
}

.block_presentation__row-rating {
  display: flex;
  font-size: 25px;
}

.block_presentation__row-rating span {
  font-weight: 800;
}

.block_presentation__row-rating img {
  margin-left: 10px;
}

.block_presentation_center {
  display: flex;
  justify-content: center;
  align-items: center;
}

.block_presentation_center p {
  font-size: 24px;
  cursor: pointer;
}

.last_days-block {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  margin-top: 35px;
}

.help-block {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 35px;
  padding-bottom: 25px;
}

.help_title {
  font-size: 40px;
}

.help_subtitle {
  font-size: 25px;
  color: #c5ccd2;
  margin-top: -15px;
  margin-bottom: 25px;
}

.last_days-block__text p {
  color: #c5ccd2;
  font-size: 25px;
}

.people_image {
  margin-left: 30px;
  margin-bottom: 15px;
  margin-right: 30px;
}

.block2 .block_presentation__row {
  align-items: center;
}

@media screen and (max-width: 1150px) {
  .block1 {
    width: 100%;
    margin-bottom: 25px;
  }

  .block2 {
    width: 100%;
    margin-bottom: 25px;
  }

  .block3 {
    width: 100%;
  }

  .content__container {
    flex-direction: column;
  }

  .content__header {
    flex-direction: column;
    align-items: center;
  }

  .content__menu-icons {
    margin-top: 20px;
  }

  .statistics_row {
    justify-content: flex-start;
  }

  .block2 .block_presentation__row {
    align-items: flex-start;
    justify-content: flex-start;
  }
}

@media screen and (max-width: 750px) {
  .content__header-menu {
    flex-wrap: wrap;
    justify-content: center;
  }

  .block1 .block_presentation__row {
    flex-direction: column;
    /* justify-content: space-between; */
    align-items: center;
  }

  .block2 .block_presentation__row {
    align-items: center;
    justify-content: center;
  }

  .block1 .block_presentation__title {
    text-align: center;
  }

  .block1 .block_presentation__subtitle {
    text-align: center;
  }

  .block2 .block_presentation__title {
    text-align: center;
  }

  .block2 .block_presentation__subtitle {
    text-align: center;
  }

  .width-auto {
    width: auto;
  }

  .block3 .block_presentation {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .flex-row {
    justify-content: center;
  }

  .block1-description {
    width: 100%;
  }

  .navigation__logo {
    width: 80px;
  }

  .block_presentation__stars {
    object-fit: contain;
  }

  .flex-column {
    flex-direction: column;
  }
}
</style>