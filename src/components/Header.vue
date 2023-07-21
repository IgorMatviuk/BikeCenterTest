<template>
    <div>
        <div class="header">
            <div class="header__top">
                <div class="header__top__contacts">
                    <div class="header__top__contacts__loc">
                        <img src="../assets/img/header/loc.svg" alt="">
                    </div>
                    <p>Архангельск-на-под</p>
                    <p>
                        ул. Дорожная, 1Е и еще 3</p>
                    <a href="tel:+78005000320">
                        <p>8 800 500-03-20</p>
                    </a>
                    <a href="tel:+78612000320">
                        <p>8 861 200-03-20</p>
                    </a>
                </div>
                <div class="header__top__menu">
                    <div class="header__top__menu__buttons">
                        <button>Ремонт и обслуживание</button>
                        <button>Прокат оборудования</button>
                    </div>
                    <ul>
                        <li>О нас</li>
                        <li>Доставка</li>
                        <li>Оплата</li>
                        <li>Вакансии</li>
                        <li>Помощь</li>
                        <li>Контакты</li>
                    </ul>
                </div>

            </div>
            <div class="header__center">
                <div class="header__center__container">
                    <div class="header__center__left">
                        <div class="header__center__logo">
                            <img src="../assets/img/header/logo.svg" alt="">
                        </div>
                        <div class="header__center__catalog-btn" v-on:mouseover="mouseover">
                            <svg width="16" height="9" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <rect y="7" width="16" height="2" rx="1" fill="white" />
                                <rect width="16" height="2" rx="1" fill="white" />
                            </svg>
                            <p>Каталог</p>
                        </div>
                        <div class="header__center__search">
                            <input type="text">
                            <div class="header__center__search__btn">
                                <img src="../assets/img/header/search.svg" alt="">
                            </div>
                        </div>
                    </div>
                    <div class="header__center__right">
                        <div class="header__center__login">
                            <img src="../assets/img/header/login.svg" alt="">
                            <p>Вход</p>
                        </div>
                        <div class="header__center__menu">
                            <div class="header__center__menu__item">
                                <img src="../assets/img/header/box.svg" alt="">
                                <p>Заказы</p>
                            </div>
                            <div class="header__center__menu__item">
                                <img src="../assets/img/header/chart.svg" alt="">
                                <p>Сравнение</p>
                            </div>
                            <div class="header__center__menu__item">
                                <img src="../assets/img/header/heart.svg" alt="">
                                <p>Избранное</p>
                            </div>
                            <div class="header__center__menu__item">
                                <img src="../assets/img/header/basket.svg" alt="">
                                <p>Корзина</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="header__bottom">
                <div class="header__bottom__container">
                    <div class="header__bottom__left">
                        <ul>
                            <li>Горные велосипеды</li>
                            <li>Детские велосипеды</li>
                            <li>Детские самокаты</li>
                            <li>Электросамокаты</li>
                        </ul>
                    </div>
                    <div class="header__bottom__right">
                        <ul>
                            <li>Распродажа</li>
                            <li>Бренды</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <div class="header-menu" v-if="IsMenuShow">
            <div class="header-menu__container">
                <div class="header-menu__left">
                    <div class="header-menu__left__menu">
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>

                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>
                        <div class="header-menu__left__menu__item">
                            <div class="header-menu__left__menu__item__container">
                                <div class="header-menu__left__menu__item__left">
                                    <div class="header-menu__left__menu__item__image"></div>
                                    <p>Велосипеды</p>
                                </div>
                                <img src="../assets/img/header/header-menu-ar.svg" alt="">
                            </div>
                        </div>

                    </div>
                </div>
                <div class="header-menu__center">
                    <div class="header-menu__center__block">
                        <div class="header-menu__center__block__title">
                            <h3>Амортизаторы и вилки</h3>
                            <div class="header-menu__center__block__title__image"></div>
                        </div>
                        <p>Амортизаторы</p>
                        <p>Вилки</p>
                        <p>Запчасти для вилок</p>
                        <p>Запчасти для амортизаторов</p>
                    </div>
                    <div class="header-menu__center__block">
                        <div class="header-menu__center__block__title">
                            <h3>Привод</h3>
                            <div class="header-menu__center__block__title__image"></div>
                        </div>
                        <p>Кассеты и трещотки</p>
                        <p>Звёзды и рокринги</p>
                        <p>Системы (шатуны)</p>
                        <p>Педали</p>
                        <p>Каретки</p>
                        <p>Цепи</p>
                        <p>Натяжители и успокоители</p>
                    </div>
                    <div class="header-menu__center__block">
                        <div class="header-menu__center__block__title">
                            <h3>Седля и подседельные
                                штыри</h3>
                            <div class="header-menu__center__block__title__image"></div>
                        </div>
                        <p>Сёдла</p>
                        <p>Штири</p>
                        <p>Подседельные зажимы</p>
                    </div>
                    <div class="header-menu__center__block">
                        <div class="header-menu__center__block__title">
                            <h3>Колёса и комплектующие</h3>
                            <div class="header-menu__center__block__title__image"></div>
                        </div>
                        <p>Покрышки</p>
                        <p>Камеры</p>
                        <p>Обода</p>
                        <p>Колеса в сборе</p>
                        <p>Втулки</p>
                        <p>Запчасти для втулок</p>
                        <p>Герметики</p>
                        <p>Наппеля</p>
                        <p>Спицы</p>
                        <p>Флипперы</p>
                    </div>
                    <div class="header-menu__center__block">
                        <div class="header-menu__center__block__title">
                            <h3>Рамы и комплектующие</h3>
                            <div class="header-menu__center__block__title__image"></div>
                        </div>
                        <p>Рамы</p>
                        <p>Петухи</p>
                        <p>Защита пера</p>
                        <p>Пеги</p>
                    </div>
                    <div class="header-menu__center__block">
                        <div class="header-menu__center__block__title">
                            <h3>Тормозные системы</h3>
                            <div class="header-menu__center__block__title__image"></div>
                        </div>
                        <p>Тормоза дисковые гидравлические</p>
                        <p>Тормоза дисковые механические</p>
                        <p>Роторы</p>
                        <p>Адаптеры</p>
                        <p>Колодки</p>
                        <p>Тормоза V-Brake</p>
                        <p>Тормоза клещевые</p>
                        <p>Тормоза кантиливерные</p>
                        <p>Тормозные ручки</p>
                        <p>Запчасти для тормозных систем</p>
                    </div>
                    <div class="header-menu__center__block">
                        <div class="header-menu__center__block__title">
                            <h3>Трансмиссия</h3>
                            <div class="header-menu__center__block__title__image"></div>
                        </div>
                        <p>Манетки</p>
                        <p>Переключатели задние</p>
                        <p>Переключтели передние</p>
                    </div>
                    <div class="header-menu__center__block">
                        <div class="header-menu__center__block__title">
                            <h3>Рулевое управление</h3>
                            <div class="header-menu__center__block__title__image"></div>
                        </div>
                        <p>Рули</p>
                        <p>Рога</p>
                        <p>Грипсы и обмотки руля</p>
                        <p>Выносы</p>
                        <p>Рулевые колонки</p>
                        <p>Якоря и проставочные кольца</p>
                    </div>
                    <div class="header-menu__center__block">
                        <div class="header-menu__center__block__title">
                            <h3>Инструменты</h3>
                            <div class="header-menu__center__block__title__image"></div>
                        </div>
                        <p>Мультитулы</p>
                        <p>Ключи специальные</p>
                        <p>Съемники</p>
                        <p>Выжимники цепи</p>
                        <p>Ремнаборы для камер и покрышек</p>
                        <p>Наборы инструментов</p>
                        <p>Монтажки</p>
                    </div>
                </div>
                <div class="header-menu__right">
                    <div class="header-menu__right__block"></div>
                    <div class="header-menu__right__block"></div>
                    <div class="header-menu__right__block"></div>
                    <div class="header-menu__right__block"></div>
                    <div class="header-menu__right__block"></div>
                    <div class="header-menu__right__block"></div>
                </div>
            </div>
        </div>
        <div class="header-mob">
            <div class="header-mob__container">
                <div class="header-mob__left">
                    <transition>
                        <div v-if="IsMenuMobShow === false">
                            <div @click="showMenuMob" class="header-mob__menu-btn">
                                <svg width="32" height="22" viewBox="0 0 32 22" xmlns="http://www.w3.org/2000/svg">
                                    <rect y="18.8575" width="32" height="3.14286" rx="1" fill="white" />
                                    <rect y="9.42871" width="32" height="3.14286" rx="1" fill="white" />
                                    <rect width="32" height="3.14286" rx="1" fill="white" />
                                </svg>
                            </div>
                        </div>
                    </transition>
                    <transition>
                        <div v-if="IsMenuMobShow">
                            <div @click="showMenuMob">
                                <svg xmlns="http://www.w3.org/2000/svg" width="23" height="23" viewBox="0 0 23 23"
                                    fill="none">
                                    <path d="M22 22L1 1M22 1L1 22" stroke="#F84445" stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" />
                                </svg>
                            </div>
                        </div>
                    </transition>
                    <div class="header-mob__logo">
                        <img src="../assets/img/header/mobile-logo.svg" alt="">
                    </div>
                </div>
                <div class="header-mob__right">
                    <div class="header-mob__search">
                        <img src="../assets/img/header/mobile search.svg" alt="">
                    </div>
                    <div class="header-mob__basket">
                        <img src="../assets/img/header/mobile basket.svg" alt="">
                    </div>
                </div>
            </div>
        </div>
        <div class="header-mob-menu" v-if="IsMenuMobShow">
            <div class="header-mob-menu__loc">
                <p>Ваш город </p>
                <div class="header-mob-menu__loc__city">
                    <img src="../assets/img/header/local.svg" alt="">
                    <p>Краснодар</p>
                </div>
            </div>
            <div class="header-mob-menu__switch">
                <label class="switch btn-color-mode-switch">
                    <input value="1" id="color_mode" name="color_mode" type="checkbox">
                    <label class="btn-color-mode-switch-inner" data-off="Каталог" data-on="Бренды" for="color_mode"></label>
                </label>
            </div>
            <div class="header-mob-menu__menu">
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>
                <div class="header-mob-menu__menu__item">
                    <div class="header-mob-menu__menu__item__left">
                        <div class="header-mob-menu__menu__item__left__image"></div>
                        <p>Велосипеды</p>
                    </div>
                    <img src="../assets/img/header/header-menu-ar.svg" alt="">
                </div>

            </div>
        </div>
    </div>
</template>
  
<script>


export default {
    data() {
        return {
            IsMenuShow: false,
            IsMenuMobShow: false,
        }
    },

    methods: {
        mouseover: function () {
            this.IsMenuShow = !this.IsMenuShow;
        },
        showMenuMob() {
            this.IsMenuMobShow = !this.IsMenuMobShow;
        },
    }
}
</script>
  
<style lang="scss"></style>