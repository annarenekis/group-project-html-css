// Footer//
//Break points
$mobile: 320px;
$tablet: 768px;
$desktop: 1200px;

$mobile-max: $tablet - 1;
$tablet-max: $desktop - 1;
/////////////////////////
.address {
    font-style: normal;
    font-weight: 700;
    font-size: 12px;
    line-height: 1.86;

    display: flex;
    justify-content: flex-end;

    @media screen and (min-width: $tablet) {
        font-size: 14px;
    }

    @media screen and (min-width: $desktop) {
        font-size: 16px;
    }
}

.address__appeal {
    margin-right: 4px;
    color: var (--main-text-color);
}

.address__tel {
    color: (--accent-color);

    &:hover {
        color: var (--complementary-text-color);
    }
}
/////////
.footer {
    background-color: var (--secondary-bg-color);
    
    @media screen and (min-width: $desktop) {
        padding-top: 60px;
    }
}
.footer__container {
    padding-bottom: 40px;


    @media screen and (min-width:$tablet) {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    @media screen and (min-width: $desktop) {
        padding-bottom: 60px;
    }
}
//////////////////
.footer-label {
    font-family: 'Titan One', cursive;
    font-weight: 400;
    text-transform: uppercase;

    @media screen and (max-width: $mobile-max) {
        margin-bottom: 40px;
    }
}

.footer-label__begin {
    display: block;
    margin-bottom: 16px;
    font-size: 18px;
    line-height: 1.167;
    ////color: var (--secondary-title-color);////

    @media screen and (max-width: $mobile-max) {
        width: 230px;
    }

    @media screen and (min-width: $tablet) and (max-width: $tablet-max) {
        width: 340px;
        margin-bottom: 12px;
    }

    @media screen and (min-width: $tablet) {
        font-size: 26px;
        line-height: 1.154;
        letter-spacing: 0.04em;
    }

    @media screen and (min-width: $desktop) {
        font-size: 30px;
        line-height: 1.133;
    }
}

.footer-label__end {
    display: block;
    font-size: 34px;
    line-height: 1, 147;
    letter-spacing: 0.04em;
    ///color: var (--accent-color);////

    @media screen and (max-width: $mobile-max) {
        width: 200px;
    }

    @media screen and (min-width: $tablet) and (max-width: $tablet-max) {
        width: 340px;
    }

    @media screen and (min-width: $tablet) {
        font-size: 48px;
        line-height: 1.146;
        letter-spacing: 0.06em;
    }

    @media screen and (min-width: $desktop) {
        font-size: 58px;
        line-height: 1.138;
    }
}
//////.page-footer__icon {
    fill: var (--secondary-text-color);}//////

.footer__copyright {
  padding-top: 16px;
  padding-bottom: 3px;
  border-top: 1px solid #e1e1e1;

  @media screen and (min-width: $tablet) {
    padding-top: 8px;
    padding-bottom: 8px;
  }

  @media screen and (min-width: $desktop) {
    padding-top: 7px;
    padding-bottom: 4px;
  }
}

.footer__copyright-text {
  font-weight: 700;
  line-height: 1.52;

  color: var(--complementary-text-color);
  text-align: center;

  @media screen and (max-width: 480px) {
    margin-right: auto;
    margin-left: auto;
    max-width: 150px;
  }

  @media screen and (min-width: $tablet) {
    line-height: 1.86;
    letter-spacing: 0.02em;
  }
}
////////////////////////////
social
.socials {
    display: flex;
    justify-content: flex-end;
    align-items: center;

    margin-bottom: 40px;
}

.socials__item {
    @include set-items-margin (right, 30px);
}

.socials__link {
    width: 34px;
    height: 34px;
    border-radius: 50%;

    background-color: var (--icons-bg-color);
    @extend %flex-center;

    transition: background-color var (--timing-transition);

    &:hover {
        background-color: var (--accent-color);
    }
}
.footer__icon {
  fill: var(--secondary-text-color);
}
///////////////
///.container{
    padding-left: 20px;
    padding-right: 20px;
    margin-left: auto;
    margin-right: auto;

    @media screen and (min-width: $tablet) {
        width: $tablet;
        padding-left: 32px;
        padding-right: 32px;
    }

    @media screen and (min-width: $desktop) {
        width: $desktop;
        padding-left: 16px;
        padding-right: 16px;
    }
}///////////////////////////

.footer__container {
  padding-bottom: 40px;
  padding-left: 20px;
    padding-right: 20px;
    margin-left: auto;
    margin-right: auto;

  @media screen and (min-width: $tablet) {
    display: flex;
    align-items: center;
    justify-content: space-between;
      width: $tablet;
        padding-left: 32px;
        padding-right: 32px;
  }

  @media screen and (min-width: $desktop) {
    padding-bottom: 60px;
    width: $desktop;
        padding-left: 16px;
        padding-right: 16px;
  }
}
///
.footer__copyright-text {
  margin: auto;
  font-weight: 700;
  font-size: 14px;
  line-height: 1.86;
  letter-spacing: 0.02em;

  color: var(--complementary-text-color);
  text-align: center;

  @media screen and (max-width: 480px) {
    // margin-right: auto;
    // margin-left: auto;
    max-width: 150px;
    line-height: 1.52;
    width: 150px;
  }
}





