&\_\_item {
margin: 0;
padding: 0;
list-style: none;
display: flex;
gap: 111px;

    font-family: $font;
    font-style: normal;

}

&\_\_img {
display: flex;
margin: 0;
padding: 0;
}

&\_\_info {
display: flex;
margin: 0;
padding: 0;

    &-leed {
      margin-top: 37px;
      width: 776px;
      font-weight: 400;
      font-size: 20px;
      line-height: 30px;
      color: $accent;
    }
    &__email {
      margin: 0;
      padding: 0;
      display: flex;
      gap: 12px;

      &-login {
        margin-top: 50px;
        width: 450px;
        height: 80px;
        border: 1px solid #8f95a5;
        border-radius: 10px;
        text-decoration: none;

        &__btn {
          background: #263238;
          border-radius: 10px;
        }
      }
    }

}
}
