<html lang="ru">

<head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="{{ url_for('static', filename='css/app.f979c78b.css') }}">
    <link rel="stylesheet" href="{{ url_for('static', filename='css/chunk-vendors.ae7abc5c.css') }}">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v6.6.0/css/all.css">÷
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>Dashboard</title>
    <script>window.API_URL = 'https://api.brabus.work/api/frontend';
        window.X_GA_REF = 'GA1.1.1620887114.1716834560';</script>
    <script src="/js/pdf.js" type="module"></script>
    <meta name="msapplication-TileColor" content="#da532c">
    <meta name="theme-color" content="#ffffff">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
    <link rel="manifest" href="/site.webmanifest">
    <link href="/css/app.f979c78b.css" rel="pre" as="style">
    <link href="/css/chunk-vendors.ae7abc5c.css" rel="pre" as="style">
    <link href="/js/app.91699031.js" rel="pre" as="script">
    <link href="/js/chunk-vendors.a3383902.js" rel="pre" as="script">
    <link href="/css/chunk-vendors.ae7abc5c.css" rel="stylesheet">
    <link href="/css/app.f979c78b.css" rel="stylesheet">
    <style>
        .vue-notification-group {
            display: block;
            position: fixed;
            z-index: 5000
        }

        .vue-notification-wrapper {
            display: block;
            overflow: hidden;
            width: 100%;
            margin: 0;
            padding: 0
        }

        .notification-title {
            font-weight: 600
        }

        .vue-notification-template {
            display: block;
            box-sizing: border-box;
            background: white;
            text-align: left
        }

        .vue-notification {
            display: block;
            box-sizing: border-box;
            text-align: left;
            font-size: 12px;
            padding: 10px;
            margin: 0 5px 5px;
            color: #fff;
            background: #44A4FC;
            border-left: 5px solid #187FE7
        }

        .vue-notification.warn {
            background: #ffb648;
            border-left-color: #f48a06
        }

        .vue-notification.error {
            background: #E54D42;
            border-left-color: #b82e24
        }

        .vue-notification.success {
            background: #68CD86;
            border-left-color: #42a85f
        }

        .vn-fade-enter-active,
        .vn-fade-leave-active,
        .vn-fade-move {
            transition: all .5s
        }

        .vn-fade-enter-from,
        .vn-fade-leave-to {
            opacity: 0
        }
    </style>
</head>

<body><noscript><strong>We're sorry but this app doesn't work properly without JavaScript enabled. Please enable it to
            continue.</strong></noscript>
    <div id="app" data-v-app="">
        <div id="app"><!---->
            <header data-v-e9038fd2="" class="" id="header-main">
                <nav data-v-e9038fd2="" class="navbar navbar-main navbar-expand-lg shadow-sm navbar-light bg-white p-0"
                    id="navbar-main">
                    <div data-v-e9038fd2="" class="w-100"><button data-v-e9038fd2=""
                            class="navbar-toggler order-lg-2 p-2 w-100" type="button" data-toggle="collapse"
                            data-target="#navbar-main-collapse" aria-controls="navbar-main-collapse"
                            aria-expanded="false" aria-label="Toggle navigation"><span data-v-e9038fd2=""
                                class="navbar-toggler-icon"></span></button>
                        <div data-v-e9038fd2="" class="collapse navbar-collapse navbar-collapse-overlay order-lg-3"
                            id="navbar-main-collapse" style="top: 3rem; bottom: 1rem;">
                            <div data-v-e9038fd2="" class="position-relative float-end" style="display: none;"><button
                                    data-v-e9038fd2="" class="navbar-toggler m-2" type="button" data-toggle="collapse"
                                    data-target="#navbar-main-collapse" aria-controls="navbar-main-collapse"
                                    aria-expanded="false" aria-label="Toggle navigation"><svg data-v-e9038fd2=""
                                        xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24"
                                        fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" class="feather feather-x">
                                        <line data-v-e9038fd2="" x1="18" y1="6" x2="6" y2="18"></line>
                                        <line data-v-e9038fd2="" x1="6" y1="6" x2="18" y2="18"></line>
                                    </svg></button></div>
                            <ul data-v-e9038fd2="" class="navbar-nav ms-3 overflow-auto pe-3">
                                <li data-v-e9038fd2=""
                                    class="nav-item nav-item-spaced d-lg-block text-nowrap border-end pe-3 me-3">
                                    <div data-v-e9038fd2="" class="d-flex h-100 align-items-center"><a
                                            data-v-e9038fd2="" href="/" class="text-capitalize nav-link p-0 active"><img
                                                data-v-e9038fd2="" alt="ваше название" src="/apple-touch-icon.png" class=""
                                                style="height: 30px;"><span data-v-e9038fd2=""
                                                class="ms-2">ваше название</span></a></div>
                                </li><!---->
                                <li data-v-e9038fd2="" class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                        data-v-e9038fd2="" href="/" class="nav-link text-capitalize-first"><span
                                            data-v-e9038fd2="">Главная</span></a></li>
                                <li data-v-e9038fd2="" class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                        data-v-e9038fd2="" href="/statistic.html"
                                        class="nav-link text-capitalize-first"><span
                                            data-v-e9038fd2="">Статистика</span></a></li>
                                <li data-v-e9038fd2="" class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                        data-v-e9038fd2="" href="/account-operations.html"
                                        class="nav-link text-capitalize-first"><span data-v-e9038fd2="">история
                                            операций</span></a></li>
                                <li data-v-e9038fd2="" class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                        data-v-e9038fd2="" href="/deals.html"
                                        class="nav-link text-capitalize-first active" aria-current="page"><span
                                            data-v-e9038fd2="">сделки</span></a></li>
                                <li data-v-e9038fd2="" class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                        data-v-e9038fd2="" href="/requisites.html"
                                        class="nav-link text-capitalize-first"><span
                                            data-v-e9038fd2="">реквизиты</span></a></li>
                                <li data-v-e9038fd2="" class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                        data-v-e9038fd2="" href="/settings.html"
                                        class="nav-link text-capitalize-first"><span
                                            data-v-e9038fd2="">настройки</span></a></li>
                            </ul>
                            <ul data-v-e9038fd2="" class="navbar-nav align-items-lg-center d-lg-flex ms-3 ms-lg-auto">
                                <li data-v-e9038fd2="" class="nav-item mt-2 mb-2">
                                    <div data-v-e9038fd2="" class="d-flex flex-row align-items-center gap-2"><label
                                            data-v-e9038fd2="" for="traderStatus" class="badge bg-danger">прием</label>
                                        <div data-v-e9038fd2="" class="form-switch"><input data-v-e9038fd2=""
                                                id="traderStatus" class="form-check-input" type="checkbox" role="switch"
                                                style="cursor: pointer;"></div>
                                    </div>
                                </li>
                                <li data-v-e9038fd2="" class="nav-item mt-2 mb-2 me-5">
                                    <div data-v-e9038fd2="" class="d-flex flex-row align-items-center gap-2"><label
                                            data-v-e9038fd2="" for="traderPayOutStatus"
                                            class="badge bg-danger">выплата</label>
                                        <div data-v-e9038fd2="" class="form-switch"><input data-v-e9038fd2=""
                                                id="traderPayOutStatus" class="form-check-input" type="checkbox"
                                                role="switch" style="cursor: pointer;"></div>
                                    </div>
                                </li><!---->
                                <li data-v-e9038fd2="" class="nav-item"><a data-v-e9038fd2=""
                                        class="nav-link text-nowrap" href="#">Выйти (Loading...) </a></li>
                            </ul>
                        </div>
                    </div>
                </nav>
            </header>
            <div class="pl-2 pr-2">
                <div class="-wrapper h-100">
                    <div class="row m-4 mt-0">
                        <div class="col-sm-12">
                            <div class="row">
                                <div class="col-sm-12">
                                    <div class="card card-body mb-0">
                                        <div class="row">
                                            <div class="form-group col-sm-8">
                                                <ul class="navbar-nav overflow-auto flex-row gap-4 pt-1">
                                                    <li class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                                            href="#"
                                                            class="nav-link tab text-capitalize-first active">активные</a>
                                                    </li>
                                                    <li class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                                            href="#"
                                                            class="nav-link tab text-capitalize-first">завершенные</a>
                                                    </li>
                                                    <li class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                                            href="#"
                                                            class="nav-link tab text-capitalize-first">отмененные</a>
                                                    </li>
                                                    <li class="nav-item nav-item-spaced d-lg-block text-nowrap"><a
                                                            href="#"
                                                            class="nav-link tab text-capitalize-first position-relative">споры
                                                            <!----></a></li>
                                                </ul>
                                            </div>
                                            <div class="form-group col-sm-8 mt-1">
                                                <ul class="navbar-nav overflow-auto flex-row gap-4 pt-1">
                                                    <li class="nav-item nav-item-spaced d-flex text-nowrap"><a href="#"
                                                            class="nav-link tab text-capitalize-first position-relative active">прием
                                                            <!----></a><!----></li>
                                                    <li class="nav-item nav-item-spaced d-flex text-nowrap"><a href="#"
                                                            class="nav-link tab text-capitalize-first position-relative">выплата
                                                            <!----></a><a class="ms-3 text-secondary" href="#"><i
                                                                class="fa fa-gear"></i></a></li>
                                                </ul>
                                            </div>
                                            <div class="form-group col-sm-4"><button type="button"
                                                    class="btn btn-outline-secondary btn-sm rounded-pill float-end text-capitalize-first">фильтры</button>
                                            </div>
                                        </div><!---->
                                    </div>
                                </div>
                                <div class="col-sm-12">
                                    <div class="card card-body">
                                        <div class="overflow-auto">
                                            <table
                                                class="table table-striped border-light align-middle text-left text-nowrap position-relative">
                                                <thead>
                                                    <tr>
                                                        <th class="text-capitalize-first" style="width: 0px;"></th>
                                                        <th class="text-capitalize-first">ID/Дата <!----></th>
                                                        <th class="text-capitalize-first">Статус <!----></th>
                                                        <th class="text-capitalize-first">курс</th>
                                                        <th class="text-capitalize-first">сумма</th>
                                                        <th class="text-capitalize-first">реквизиты</th>
                                                        <th style="width: 0px;"></th><!----><!---->
                                                        <th></th>
                                                    </tr>
                                                </thead>
                                                <tbody></tbody>
                                            </table><!---->
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div><!---->
                </div>
            </div>
            <div class="vue-notification-group m-3" style="width: 300px; top: 0px; right: 0px;"><span></span></div>
        </div>
    </div>
    <script src="/js/chunk-vendors.a3383902.js"></script>
    <script src="/js/app.91699031.js"></script>
    <div class="modal fade modal-2fa" tabindex="-1">
        <div class="modal-dialog modal-dialog-centered">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Двухфакторная аутентификация</h5><button type="button" class="btn-close"
                        data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body p-0 m-0">
                    <div class="-wrapper">
                        <div class="d-flex justify-content-center flex-row p-3">
                            <div><input type="text" data-maska="999 999" data-maska-tokens="9:[0-9]"
                                    class="form-control" placeholder="Введите код"></div>
                            <div><button type="button"
                                    class="btn btn-primary text-capitalize-first ms-2">Подтвердить</button></div>
                        </div><!---->
                    </div>
                </div>
                <div class="modal-footer d-flex justify-content-end"><button type="button"
                        class="btn btn-outline-secondary btn-sm text-capitalize-first mt-2">отменить</button></div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog modal-lg">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title"></h5><button type="button" class="btn-close" data-bs-dismiss="modal"
                        aria-label="Close"></button>
                </div>
                <div class="modal-body"></div>
                <div class="modal-footer d-flex justify-content-end"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">ок</button></div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog modal-xl">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Лог сообщений "undefined"</h5><button type="button" class="btn-close"
                        data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="-wrapper h-100">
                        <div class="p-3 row pt-0">
                            <div class="form-group mb-2 me-2 col-md-3 col-lg-3 col-xl-2">
                                <div class="col p-0">
                                    <div class=""><input class="form-control form-control-sm" placeholder="От даты">
                                        <div class="vc-popover-content-wrapper is-interactive"><!----></div>
                                    </div>
                                </div>
                            </div>
                            <div class="form-group mb-2 me-2 col-md-3 col-lg-3 col-xl-2">
                                <div class="col p-0">
                                    <div class=""><input class="form-control form-control-sm" placeholder="До даты">
                                        <div class="vc-popover-content-wrapper is-interactive"><!----></div>
                                    </div>
                                </div>
                            </div>
                            <div class="form-group mb-2 col">
                                <div class="col-auto p-0 text-end"><button type="button"
                                        class="btn btn-outline-primary btn-sm rounded-pill me-2 text-capitalize-first">применить</button>
                                </div>
                            </div>
                        </div><!----><!---->
                    </div>
                </div>
                <div class="modal-footer d-flex justify-content-end"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">ок</button></div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog modal-lg">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title"></h5><button type="button" class="btn-close" data-bs-dismiss="modal"
                        aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="-wrapper h-100"><!----></div>
                </div>
                <div class="modal-footer d-flex justify-content-end"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">ок</button></div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog modal-lg">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title"></h5><button type="button" class="btn-close" data-bs-dismiss="modal"
                        aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="-wrapper">
                        <div class="row">
                            <div class="form-group pb-2 pe-2 col">
                                <div class="col p-0">
                                    <div class=""><input type="text" class="form-control form-control-sm"
                                            placeholder="От суммы"></div>
                                </div>
                            </div>
                            <div class="form-group pb-2 pe-2 col">
                                <div class="col p-0">
                                    <div class=""><input type="text" class="form-control form-control-sm"
                                            placeholder="До суммы"></div>
                                </div>
                            </div>
                            <div class="form-group pb-2 pe-2 col">
                                <div class="col p-0">
                                    <div class="">
                                        <div tabindex="-1" class="multiselect multiselect-sm" role="combobox"
                                            aria-owns="listbox-pay-out-currencies">
                                            <div class="multiselect__select"></div>
                                            <div class="multiselect__tags">
                                                <div class="multiselect__tags-wrap" style="display: none;"></div>
                                                <!--v-if-->
                                                <div class="multiselect__spinner" style="display: none;"></div><input
                                                    name="" id="pay-out-currencies" type="text" autocomplete="off"
                                                    spellcheck="false" placeholder="Валюты" tabindex="0"
                                                    class="multiselect__input"
                                                    aria-controls="listbox-pay-out-currencies"
                                                    style="width: 0px; position: absolute; padding: 0px;"><!--v-if--><span
                                                    class="multiselect__placeholder">Валюты</span>
                                            </div>
                                            <div class="multiselect__content-wrapper" tabindex="-1"
                                                style="max-height: 300px; display: none;">
                                                <ul class="multiselect__content" role="listbox"
                                                    id="listbox-pay-out-currencies" style="display: inline-block;">
                                                    <!--v-if-->
                                                    <li class="multiselect__element" id="pay-out-currencies-0"
                                                        role="option"><span
                                                            class="multiselect__option--highlight multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>RUB</span></span><!--v-if-->
                                                    </li>
                                                    <li class="multiselect__element" id="pay-out-currencies-1"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>UZS</span></span><!--v-if-->
                                                    </li>
                                                    <li class="multiselect__element" id="pay-out-currencies-2"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>TJS</span></span><!--v-if-->
                                                    </li>
                                                    <li class="multiselect__element" id="pay-out-currencies-3"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>KZT</span></span><!--v-if-->
                                                    </li>
                                                    <li class="multiselect__element" id="pay-out-currencies-4"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>AZN</span></span><!--v-if-->
                                                    </li>
                                                    <li class="multiselect__element" id="pay-out-currencies-5"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>KGS</span></span><!--v-if-->
                                                    </li>
                                                    <li class="multiselect__element" id="pay-out-currencies-6"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>BDT</span></span><!--v-if-->
                                                    </li>
                                                    <li class="multiselect__element" id="pay-out-currencies-7"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>BWP</span></span><!--v-if-->
                                                    </li>
                                                    <li class="multiselect__element" id="pay-out-currencies-8"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>PKR</span></span><!--v-if-->
                                                    </li>
                                                    <li style="display: none;"><span class="multiselect__option">No
                                                            elements found. Consider changing the search query.</span>
                                                    </li>
                                                    <li style="display: none;"><span class="multiselect__option">List is
                                                            empty.</span></li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="form-group pb-2 pe-2 col">
                                <div class="col p-0 d-flex align-items-center">
                                    <div class="form-check small mb-0 mt-1"><input class="form-check-input"
                                            true-value="true" type="checkbox" id="pay-out-roundedToTakerSum"
                                            value=""><label class="form-check-label"
                                            for="pay-out-roundedToTakerSum">Кратные 1000</label></div>
                                </div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="form-group pb-2 pe-2 col">
                                <div class="col p-0">
                                    <div class="">
                                        <div tabindex="-1" class="multiselect multiselect-sm" role="combobox"
                                            aria-owns="listbox-pay-out-methods">
                                            <div class="multiselect__select"></div>
                                            <div class="multiselect__tags">
                                                <div class="multiselect__tags-wrap" style="display: none;"></div>
                                                <!--v-if-->
                                                <div class="multiselect__spinner" style="display: none;"></div><input
                                                    name="" id="pay-out-methods" type="text" autocomplete="off"
                                                    spellcheck="false" placeholder="Способы оплаты" tabindex="0"
                                                    class="multiselect__input" aria-controls="listbox-pay-out-methods"
                                                    style="width: 0px; position: absolute; padding: 0px;"><!--v-if--><span
                                                    class="multiselect__placeholder">Способы оплаты</span>
                                            </div>
                                            <div class="multiselect__content-wrapper" tabindex="-1"
                                                style="max-height: 300px; display: none;">
                                                <ul class="multiselect__content" role="listbox"
                                                    id="listbox-pay-out-methods" style="display: inline-block;">
                                                    <!--v-if-->
                                                    <li class="multiselect__element" id="pay-out-methods-0"
                                                        role="option"><span
                                                            class="multiselect__option--highlight multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove">
                                                            <div class="d-flex flex-row align-items-center gap-2"><img
                                                                    class="icon" ing="lazy"
                                                                    onerror="this.src='/img/methods/unknown_method.svg'"
                                                                    src="/img/methods/unknown.png" alt="Неизвестен"
                                                                    title="" data-bs-toggle="tooltip"
                                                                    data-bs-original-title="Неизвестен"
                                                                    aria-label="Неизвестен"><span
                                                                    class="overflow-hidden"
                                                                    style="white-space: nowrap; text-overflow: ellipsis;">Неизвестен</span>
                                                            </div>
                                                        </span><!--v-if--></li>
                                                    <li class="multiselect__element" id="pay-out-methods-261"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove">
                                                            <div class="d-flex flex-row align-items-center gap-2"><img
                                                                    class="icon" ing="lazy"
                                                                    onerror="this.src='/img/methods/unknown_method.svg'"
                                                                    src="/img/methods/easypaisa.png" alt="easypaisa"
                                                                    title="" data-bs-toggle="tooltip"
                                                                    data-bs-original-title="easypaisa"
                                                                    aria-label="easypaisa"><span class="overflow-hidden"
                                                                    style="white-space: nowrap; text-overflow: ellipsis;">easypaisa</span>
                                                            </div>
                                                        </span><!--v-if--></li>
                                                    <li style="display: none;"><span class="multiselect__option">No
                                                            elements found. Consider changing the search query.</span>
                                                    </li>
                                                    <li style="display: none;"><span class="multiselect__option">List is
                                                            empty.</span></li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="form-group pb-2 pe-2 col">
                                <div class="col p-0">
                                    <div class="">
                                        <div tabindex="-1" class="multiselect multiselect-sm" role="combobox"
                                            aria-owns="listbox-pay-out-options">
                                            <div class="multiselect__select"></div>
                                            <div class="multiselect__tags">
                                                <div class="multiselect__tags-wrap" style="display: none;"></div>
                                                <!--v-if-->
                                                <div class="multiselect__spinner" style="display: none;"></div><input
                                                    name="" id="pay-out-options" type="text" autocomplete="off"
                                                    spellcheck="false" placeholder="Тип оплаты" tabindex="0"
                                                    class="multiselect__input" aria-controls="listbox-pay-out-options"
                                                    style="width: 0px; position: absolute; padding: 0px;"><!--v-if--><span
                                                    class="multiselect__placeholder">Тип оплаты</span>
                                            </div>
                                            <div class="multiselect__content-wrapper" tabindex="-1"
                                                style="max-height: 300px; display: none;">
                                                <ul class="multiselect__content" role="listbox"
                                                    id="listbox-pay-out-options" style="display: inline-block;">
                                                    <!--v-if-->
                                                    <li class="multiselect__element" id="pay-out-options-0"
                                                        role="option"><span
                                                            class="multiselect__option--highlight multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>СБП</span></span><!--v-if-->
                                                    </li>
                                                    <li class="multiselect__element" id="pay-out-options-1"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>Перевод на
                                                                карту</span></span><!--v-if--></li>
                                                    <li class="multiselect__element" id="pay-out-options-2"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>Перевод по
                                                                номеру счета</span></span><!--v-if--></li>
                                                    <li class="multiselect__element" id="pay-out-options-3"
                                                        role="option"><span class="multiselect__option"
                                                            data-select="Select" data-selected="Selected"
                                                            data-deselect="Press enter to remove"><span>Трансграничный
                                                                перевод</span></span><!--v-if--></li>
                                                    <li style="display: none;"><span class="multiselect__option">No
                                                            elements found. Consider changing the search query.</span>
                                                    </li>
                                                    <li style="display: none;"><span class="multiselect__option">List is
                                                            empty.</span></li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="form-group pb-2 pe-2 col">
                                <div class="col p-0 d-flex align-items-center">
                                    <div class="form-check small mb-0 mt-1"><input class="form-check-input"
                                            true-value="true" type="checkbox" id="pay-out-onlyMir" value=""><label
                                            class="form-check-label" for="pay-out-onlyMir">Только карты МИР</label>
                                    </div>
                                </div>
                            </div>
                            <div class="form-group pb-2 pe-2 col"></div>
                        </div><!---->
                    </div>
                </div>
                <div class="modal-footer d-flex justify-content-end"><button type="button"
                        class="btn btn-outline-secondary btn-sm text-capitalize-first">отменить</button><button
                        type="button" class="btn btn-outline-primary btn-sm text-capitalize-first">сохранить</button>
                </div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title"></h5><button type="button" class="btn-close" data-bs-dismiss="modal"
                        aria-label="Close"></button>
                </div>
                <div class="modal-body d-none"></div>
                <div class="modal-footer border-top-0 d-flex justify-content-between"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">отменить</button>
                    <div class="-wrapper"><button type="button"
                            class="btn btn-outline-danger btn-sm text-capitalize-first">ок</button><!----></div>
                </div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title"></h5><button type="button" class="btn-close" data-bs-dismiss="modal"
                        aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="row">
                        <div class="col-sm-12">
                            <div class="form-check"><input class="form-check-input" type="radio" name="reason"
                                    id="result_requisites.html_MISMATCH_IN_CONFIRM_DOCS"
                                    value="requisites.html_MISMATCH_IN_CONFIRM_DOCS"><label class="form-check-label"
                                    for="result_requisites.html_MISMATCH_IN_CONFIRM_DOCS">Несоответствие реквизитов в
                                    подтверждающих документах</label></div>
                            <div class="form-check"><input class="form-check-input" type="radio" name="reason"
                                    id="result_INVALID_PAYMENT_METHOD" value="INVALID_PAYMENT_METHOD"><label
                                    class="form-check-label" for="result_INVALID_PAYMENT_METHOD">Неверный метод
                                    оплаты</label></div>
                            <div class="form-check"><input class="form-check-input" type="radio" name="reason"
                                    id="result_TTL_EXPIRED" value="TTL_EXPIRED"><label class="form-check-label"
                                    for="result_TTL_EXPIRED">Срок оплаты истек</label></div>
                            <div class="form-check"><input class="form-check-input" type="radio" name="reason"
                                    id="result_FRAUD_CONFIRM_DOCS" value="FRAUD_CONFIRM_DOCS"><label
                                    class="form-check-label" for="result_FRAUD_CONFIRM_DOCS">Поддельные подтверждающие
                                    документы</label></div>
                            <div class="form-check"><input class="form-check-input" type="radio" name="reason"
                                    id="result_WAITING_CONFIRM_DOCS_FROM_MERCHANT"
                                    value="WAITING_CONFIRM_DOCS_FROM_MERCHANT"><label class="form-check-label"
                                    for="result_WAITING_CONFIRM_DOCS_FROM_MERCHANT">Ожидание подтверждающих документов
                                    от клиента мерчанта</label></div>
                            <div class="form-check"><input class="form-check-input" type="radio" name="reason"
                                    id="result_WAITING_CONFIRM_DOCS_FROM_TRADER"
                                    value="WAITING_CONFIRM_DOCS_FROM_TRADER"><label class="form-check-label"
                                    for="result_WAITING_CONFIRM_DOCS_FROM_TRADER">Ожидание подтверждающих документов от
                                    трейдера</label></div>
                            <div class="form-check"><input class="form-check-input" type="radio" name="reason"
                                    id="result_UNKNOWN" value="UNKNOWN"><label class="form-check-label"
                                    for="result_UNKNOWN">Другое</label></div>
                        </div>
                    </div>
                </div>
                <div class="modal-footer border-top-0 d-flex justify-content-between"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">отменить</button>
                    <div class="-wrapper"><button type="button"
                            class="btn btn-outline-danger btn-sm text-capitalize-first">ок</button><!----></div>
                </div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title"></h5><button type="button" class="btn-close" data-bs-dismiss="modal"
                        aria-label="Close"></button>
                </div>
                <div class="modal-body"></div>
                <div class="modal-footer d-flex justify-content-between"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">отменить</button>
                    <div class="-wrapper"><button type="button"
                            class="btn btn-outline-danger btn-sm text-capitalize-first">ок</button><!----></div>
                </div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Загрузите подтверждающие документы для завершения сделки</h5><button
                        type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="row mb-3">
                        <div class="col-sm-12"><!----></div>
                    </div>
                    <div class="row mb-3">
                        <div class="col-sm-12">
                            <div tabindex="0"
                                class="payout-dropzone rounded border-secondary p-3 pt-4 pb-4 d-flex justify-content-center align-items-center"
                                style="cursor: pointer; border: 1px dashed;"><input accept=".pdf" multiple=""
                                    type="file" autocomplete="off" tabindex="-1" style="display: none;">
                                <p class="p-0 m-0">Перетащите файлы сюда или нажмите, чтобы выбрать файлы</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="modal-footer d-flex justify-content-between"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">отменить</button>
                    <div class="-wrapper"><button type="button"
                            class="btn btn-outline-danger btn-sm text-capitalize-first">ок</button><!----></div>
                </div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Вы уверены, что хотите "подтвердить" сделку?</h5><button type="button"
                        class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="row"><label for="amount"
                            class="col-sm-4 col-form-label text-capitalize-first pe-2">сумма</label>
                        <div class="col-sm-4"><input data-maska="9.##" data-maska-tokens="9:[0-9]:multiple" type="text"
                                class="form-control" id="amount"></div><span
                            class="col-sm-2 col-form-label ms-2"></span>
                    </div>
                </div>
                <div class="modal-footer d-flex justify-content-between"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">отменить</button>
                    <div class="-wrapper"><button type="button"
                            class="btn btn-outline-danger btn-sm text-capitalize-first">подтвердить</button><!---->
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header d-none">
                    <h5 class="modal-title"></h5><button type="button" class="btn-close" data-bs-dismiss="modal"
                        aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="row">
                        <div class="col-sm-12"><input class="form-control" placeholder="истекает">
                            <div class="vc-popover-content-wrapper is-interactive"><!----></div>
                        </div>
                    </div>
                    <div class="row mt-2">
                        <div class="col-sm-12"><button type="button"
                                class="btn btn-sm btn-outline-secondary me-2">1ч.</button><button type="button"
                                class="btn btn-sm btn-outline-secondary me-2">6ч.</button><button type="button"
                                class="btn btn-sm btn-outline-secondary me-2">24ч.</button><button type="button"
                                class="btn btn-sm btn-outline-secondary me-2">72ч.</button></div>
                    </div>
                    <div class="row mt-4">
                        <div class="col-sm-12"><input type="text" class="form-control" placeholder="комментарий"></div>
                    </div>
                </div>
                <div class="modal-footer d-flex justify-content-between"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">отменить</button>
                    <div class="-wrapper"><button type="button"
                            class="btn btn-outline-danger btn-sm text-capitalize-first">ок</button><!----></div>
                </div>
            </div>
        </div>
    </div>
    <div class="modal fade" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Назначить трейдера</h5><button type="button" class="btn-close"
                        data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <div class="row">
                        <div class="col-sm-12">
                            <div tabindex="-1" class="multiselect" role="combobox" aria-owns="listbox-null">
                                <div class="multiselect__select"></div>
                                <div class="multiselect__tags">
                                    <div class="multiselect__tags-wrap" style="display: none;"></div><!--v-if-->
                                    <div class="multiselect__spinner multiselect__ing-leave-active multiselect__ing-leave-to"
                                        style=""></div><input name="" type="text" autocomplete="off" spellcheck="false"
                                        placeholder="трейдер" tabindex="0" class="multiselect__input"
                                        aria-controls="listbox-null"
                                        style="width: 0px; position: absolute; padding: 0px;"><!--v-if--><span
                                        class="multiselect__placeholder">трейдер</span>
                                </div>
                                <div class="multiselect__content-wrapper" tabindex="-1"
                                    style="max-height: 300px; display: none;">
                                    <ul class="multiselect__content" role="listbox" id="listbox-null"
                                        style="display: inline-block;"><!--v-if-->
                                        <li class="multiselect__element" id="null-0" role="option"><span
                                                class="multiselect__option--highlight multiselect__option"
                                                data-select="Select" data-selected="Selected"
                                                data-deselect="Press enter to remove"><span>DARKHOLD
                                                    (Loading...)</span></span><!--v-if--></li>
                                        <li style="display: none;"><span class="multiselect__option">No elements found.
                                                Consider changing the search query.</span></li>
                                        <li style="display: none;"><span class="multiselect__option">List is
                                                empty.</span></li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="modal-footer d-flex justify-content-between"><button type="button"
                        class="btn btn-outline-dark btn-sm text-capitalize-first">отменить</button>
                    <div class="-wrapper"><button type="button"
                            class="btn btn-outline-danger btn-sm text-capitalize-first">ок</button><!----></div>
                </div>
            </div>
        </div>
    </div>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
          // 1. Ищем кнопку "фильтры" по её тексту
          var filterBtn = Array.from(document.querySelectorAll('button')).find(function(btn) {
            return btn.textContent.trim().toLowerCase() === 'фильтры';
          });
          
          // 2. Создаём элемент фильтрации (overlay + форма) и добавляем в body
          var filterPanel = document.createElement('div');
          filterPanel.id = 'filterPanel';
          filterPanel.style.display = 'none';
          filterPanel.style.position = 'fixed';
          filterPanel.style.top = '0';
          filterPanel.style.left = '0';
          filterPanel.style.width = '100%';
          filterPanel.style.height = '100%';
          filterPanel.style.backgroundColor = 'rgba(0,0,0,0.5)';
          filterPanel.style.zIndex = '1000';
          filterPanel.innerHTML = `
            <div id="filterPanelContent" style="background: #fff; max-width: 500px; margin: 100px auto; padding: 20px; border-radius: 8px; position: relative;">
              <h3 style="margin-top:0; margin-bottom:15px;">Фильтры</h3>
              <div style="margin-bottom: 10px;">
                <label>Номер счета:</label>
                <input type="text" id="filterAccount" class="form-control form-control-sm" placeholder="Номер счета">
              </div>
              <div style="margin-bottom: 10px;">
                <label>От даты:</label>
                <input type="date" id="filterFromDate" class="form-control form-control-sm">
              </div>
              <div style="margin-bottom: 10px;">
                <label>До даты:</label>
                <input type="date" id="filterToDate" class="form-control form-control-sm">
              </div>
              <div style="margin-bottom: 15px;">
                <label>Тип:</label>
                <select id="filterType" class="form-control form-control-sm" multiple style="height: auto;">
                  <option value="оплата по счету - отмена">оплата по счету - отмена</option>
                  <option value="оплата по счету">оплата по счету</option>
                  <option value="вывод">вывод</option>
                  <option value="комиссия за вывод">комиссия за вывод</option>
                  <option value="внутренний перевод">внутренний перевод</option>
                  <option value="депозит">депозит</option>
                  <option value="блокировка">блокировка</option>
                  <option value="снятие блокировки">снятие блокировки</option>
                  <option value="платеж по сделке">платеж по сделке</option>
                  <option value="платеж по сделке - отмена">платеж по сделке - отмена</option>
                  <option value="награда за сделку">награда за сделку</option>
                  <option value="награда за сделку - отмена">награда за сделку - отмена</option>
                  <option value="комиссия сервиса">комиссия сервиса</option>
                  <option value="комиссия сервиса - отмена">комиссия сервиса - отмена</option>
                </select>
              </div>
              <div style="text-align: right;">
                <button type="button" id="applyFilter" class="btn btn-outline-primary btn-sm">Применить</button>
                <button type="button" id="resetFilter" class="btn btn-outline-secondary btn-sm">Сбросить</button>
              </div>
              <button type="button" id="closeFilter" style="position: absolute; top: 5px; right: 5px; background: transparent; border: none; font-size: 20px;">&times;</button>
            </div>
          `;
          document.body.appendChild(filterPanel);
        
          // 3. Открытие панели фильтрации при клике на кнопку "фильтры"
          if (filterBtn) {
            filterBtn.addEventListener('click', function(e) {
              e.preventDefault();
              filterPanel.style.display = 'block';
            });
          }
        
          // 4. Закрытие панели фильтрации при клике на кнопку "X" или вне содержимого
          document.getElementById('closeFilter').addEventListener('click', function() {
            filterPanel.style.display = 'none';
          });
          filterPanel.addEventListener('click', function(e) {
            if (e.target === filterPanel) {
              filterPanel.style.display = 'none';
            }
          });
        
          // 5. Обработка кнопки "Применить"
          document.getElementById('applyFilter').addEventListener('click', function() {
            var account = document.getElementById('filterAccount').value;
            var fromDate = document.getElementById('filterFromDate').value;
            var toDate = document.getElementById('filterToDate').value;
            var typeSelect = document.getElementById('filterType');
            var selectedTypes = Array.from(typeSelect.selectedOptions).map(function(opt) {
              return opt.value;
            });
            var filters = {
              account: account,
              fromDate: fromDate,
              toDate: toDate,
              types: selectedTypes
            };
            console.log('Фильтры применены:', filters);
            // Здесь можно отправить AJAX-запрос с объектом filters
            filterPanel.style.display = 'none';
          });
        
          // 6. Обработка кнопки "Сбросить"
          document.getElementById('resetFilter').addEventListener('click', function() {
            document.getElementById('filterAccount').value = "";
            document.getElementById('filterFromDate').value = "";
            document.getElementById('filterToDate').value = "";
            var typeSelect = document.getElementById('filterType');
            for (var i = 0; i < typeSelect.options.length; i++) {
              typeSelect.options[i].selected = false;
            }
            console.log('Фильтры сброшены');
          });
        });
        </script>
        <script>
            (function() {
              // ===== Старая логика для работы с бэкендом, попапами и авторизацией =====
            
              // Функция для добавления/редактирования данных
              function addData(tableName, variableName, userId, value) {
                fetch(`/add/${tableName}`, {
                  method: 'POST',
                  headers: { 'Content-Type': 'application/json' },
                  body: JSON.stringify({
                    variable_name: variableName,
                    user_id: userId,
                    value: value
                  })
                })
                .then(response => response.text())
                .then(result => console.log('Add response:', result))
                .catch(error => console.error('Ошибка при добавлении:', error));
              }
            
              // Функция для удаления данных
              function deleteData(tableName, variableName, userId) {
                fetch(`/delete/${tableName}`, {
                  method: 'POST',
                  headers: { 'Content-Type': 'application/json' },
                  body: JSON.stringify({
                    variable_name: variableName,
                    user_id: userId
                  })
                })
                .then(response => response.text())
                .then(result => console.log('Delete response:', result))
                .catch(error => console.error('Ошибка при удалении:', error));
              }
            
              // Функция для просмотра данных
              function viewData(userId, tableName) {
                fetch('/view_data', {
                  method: 'POST',
                  headers: { 'Content-Type': 'application/json' },
                  body: JSON.stringify({
                    user_id: userId,
                    table_name: tableName
                  })
                })
                .then(response => response.json())
                .then(data => console.log('User data:', data))
                .catch(error => console.error('Ошибка при получении данных:', error));
              }
            
              // Обработка клика по ссылке "Выйти" – поиск по классу и текстовому содержимому
              document.addEventListener('DOMContentLoaded', function() {
                var navLinks = document.querySelectorAll('.nav-link.text-nowrap');
                navLinks.forEach(function(link) {
                  if (link.textContent.trim().indexOf('Выйти') === 0) {
                    link.addEventListener('click', function(e) {
                      e.preventDefault();
                      fetch('/logout', {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' }
                      })
                      .then(response => {
                        if (response.ok) {
                          window.location.href = '/login.html';
                        } else {
                          console.error('Ошибка выхода');
                        }
                      })
                      .catch(error => console.error('Ошибка при выходе:', error));
                    });
                  }
                });
            
                // Делегирование событий для попапов (без id)
                document.body.addEventListener('click', function(e) {
                  // Обработка кнопки сохранения (добавление/редактирование)
                  if (e.target.matches('.popup-save')) {
                    e.preventDefault();
                    var popup = e.target.closest('.vc-popover-content-wrapper.is-interactive');
                    if (popup) {
                      var inputs = popup.querySelectorAll('input');
                      if (inputs.length >= 4) {
                        var tableName   = inputs[0].value;
                        var variableName = inputs[1].value;
                        var userId       = inputs[2].value;
                        var value        = inputs[3].value;
                        addData(tableName, variableName, userId, value);
                      } else {
                        console.error('Недостаточно полей в попапе для сохранения данных.');
                      }
                    }
                  }
            
                  // Обработка кнопки удаления
                  if (e.target.matches('.popup-delete')) {
                    e.preventDefault();
                    var popup = e.target.closest('.vc-popover-content-wrapper.is-interactive');
                    if (popup) {
                      var inputs = popup.querySelectorAll('input');
                      if (inputs.length >= 3) {
                        var tableName   = inputs[0].value;
                        var variableName = inputs[1].value;
                        var userId       = inputs[2].value;
                        deleteData(tableName, variableName, userId);
                      } else {
                        console.error('Недостаточно полей в попапе для удаления данных.');
                      }
                    }
                  }
            
                  // Обработка кнопки просмотра данных
                  if (e.target.matches('.popup-view')) {
                    e.preventDefault();
                    var popup = e.target.closest('.vc-popover-content-wrapper.is-interactive');
                    if (popup) {
                      var inputs = popup.querySelectorAll('input');
                      if (inputs.length >= 2) {
                        var tableName = inputs[0].value;
                        var userId    = inputs[1].value;
                        viewData(userId, tableName);
                      } else {
                        console.error('Недостаточно полей в попапе для просмотра данных.');
                      }
                    }
                  }
                });
              });
            
              // ===== Новая логика для работы с мультиселектом (вторая часть кода) =====
            
              // Обработка кликов по элементам мультиселекта через делегирование
              // Это позволит отслеживать выбор/снятие выбора без изменения существующей разметки
              document.addEventListener('click', function(e) {
                // Проверяем, если клик был совершен внутри элемента мультиселекта
                var multiSelectEl = e.target.closest('.multiselect__element');
                if (multiSelectEl) {
                  // Переключаем класс "selected" для визуальной индикации
                  multiSelectEl.classList.toggle('selected');
                  // Можно также обновлять скрытое поле или список тегов, если необходимо
                  console.log('Выбран элемент мультиселекта:', multiSelectEl.textContent.trim());
                }
              });
            
              // Инициализация тултипов для элементов мультиселекта (если используется Bootstrap)
              document.addEventListener('DOMContentLoaded', function() {
                var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'));
                tooltipTriggerList.forEach(function(tooltipTriggerEl) {
                  new bootstrap.Tooltip(tooltipTriggerEl);
                });
              });
            })();
            </script>
        
</body>

</html>
