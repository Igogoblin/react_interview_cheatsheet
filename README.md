### Содержание

| №   | Вопрос                                                                                                                                                                                               |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Что такое React?](#что-такое-react)                                                                                                                                                                 |
| 2   | [Какие основные преимущества использования React?](#какие-основные-преимущества-использования-react)                                                                                                 |
| 3   | [Что такое JSX?](#что-такое-jsx)                                                                                                                                                                     |
| 4   | [Какие основные различия между компонентами классов и функциональными компонентами в React?](#какие-основные-различия-между-компонентами-классов-и-функциональными-компонентами-в-react)             |
| 5   | [Что такое Virtual DOM, и как он работает?](#что-такое-virtual-dom-и-как-он-работает)                                                                                                                |
| 6   | [Какие методы жизненного цикла компонентов вы знаете?](#какие-методы-жизненного-цикла-компонентов-вы-знаете)                                                                                         |
| 7   | [Что такое "состояние" (state) компонента в React?](#что-такое-состояние-state-компонента-в-react)                                                                                                   |
| 8   | [Как обновить состояние компонента?](#как-обновить-состояние-компонента)                                                                                                                             |
| 9   | [Что такое пропсы (props) в React?](#что-такое-пропсы-props-в-react)                                                                                                                                 |
| 10  | [В чем разница между состоянием и пропсами?](#в-чем-разница-между-состоянием-и-пропсами)                                                                                                             |
| 11  | [Как обрабатывать события в React?](#как-обрабатывать-события-в-react)                                                                                                                               |
| 12  | [Что такое условный рендеринг в React?](#что-такое-условный-рендеринг-в-react)                                                                                                                       |
| 13  | [Как передать данные между компонентами вверх и вниз по иерархии?](#как-передать-данные-между-компонентами-вверх-и-вниз-по-иерархии)                                                                 |
| 14  | [Как выполнить HTTP-запросы в React?](#как-выполнить-http-запросы-в-react)                                                                                                                           |
| 15  | [Что такое контекст (context) в React и для чего он используется?](#что-такое-контекст-context-в-react-и-для-чего-он-используется)                                                                   |
| 16  | [Как реализовать PureComponent?](#как-реализовать-purecomponent)                                                                                                                                     |
| 17  | [Что такое ключи (keys) в списках React-элементов и зачем они нужны?](#что-такое-ключи-keys-в-списках-react-элементов-и-зачем-они-нужны)                                                             |
| 18  | [Как использовать стили в React-компонентах?](#как-использовать-стили-в-react-компонентах)                                                                                                           |
| 19  | [Что такое "управляемые компоненты" (controlled components)?](#что-такое-управляемые-компоненты-controlled-components)                                                                               |
| 20  | [Что такое "неуправляемые компоненты" (uncontrolled components)?](#что-такое-неуправляемые-компоненты-uncontrolled-components)                                                                       |
| 21  | [Как создать форму в React?](#как-создать-форму-в-react)                                                                                                                                             |
| 22  | [Что такое "подъем состояния" (lifting state up)?](#что-такое-подъем-состояния-lifting-state-up)                                                                                                     |
| 23  | [Как реализовать условное добавление класса к элементу в React?](#как-реализовать-условное-добавление-класса-к-элементу-в-react)                                                                     |
| 24  | [Что такое фрагменты (fragments) в React?](#что-такое-фрагменты-fragments-в-react)                                                                                                                   |
| 25  | [Каким образом можно оптимизировать производительность React-приложения?](#каким-образом-можно-оптимизировать-производительность-react-приложения)                                                   |
| 26  | [Что такое HOC (Higher-Order Component) в React?](#что-такое-hoc-higher-order-component-в-react)                                                                                                     |
| 27  | [В чем разница между HOC и компонентами рендер-пропсов (render props)?](#в-чем-разница-между-hoc-и-компонентами-рендер-пропсов-render-props)                                                         |
| 28  | [Что такое рефы (refs) в React и как они используются?](#что-такое-рефы-refs-в-react-и-как-они-используются)                                                                                         |
| 29  | [Как реализовать анимацию в React-приложении?](#как-реализовать-анимацию-в-react-приложении)                                                                                                         |
| 30  | [Как работает механизм "контекста" (context) для передачи данных?](#как-работает-механизм-контекста-context-для-передачи-данных)                                                                     |
| 31  | [Что такое порталы (portals) в React?](#что-такое-порталы-portals-в-react)                                                                                                                           |
| 32  | [Как реализовать lazy loading в React с использованием Suspense?](#как-реализовать-lazy-loading-в-react-с-использованием-suspense)                                                                   |
| 33  | [Какие нововведения были добавлены в React 16?](#какие-нововведения-были-добавлены-в-react-16)                                                                                                       |
| 34  | [Как использовать React DevTools для отладки приложения?](#как-использовать-react-devtools-для-отладки-приложения)                                                                                   |
| 35  | [Что такое "хуки" (hooks) в React и для чего они используются?](#что-такое-хуки-hooks-в-react-и-для-чего-они-используются)                                                                           |
| 36  | [Как создать собственный хук в React?](#как-создать-собственный-хук-в-react)                                                                                                                         |
| 37  | [Как обрабатывать ошибки в React-приложении с помощью Error Boundary?](#как-обрабатывать-ошибки-в-react-приложении-с-помощью-error-boundary)                                                         |
| 38  | [Как работает алгоритм согласования (reconciliation) в React?](#как-работает-алгоритм-согласования-reconciliation-в-react)                                                                           |
| 39  | [Какие популярные библиотеки для управления состоянием вы знаете, помимо встроенного `useState`?](#какие-популярные-библиотеки-для-управления-состоянием-вы-знаете-помимо-встроенного-usestate)      |
| 40  | [Каким образом можно оптимизировать рендеринг компонентов в React?](#каким-образом-можно-оптимизировать-рендеринг-компонентов-в-react)                                                               |
| 41  | [Что такое "глубокое сравнение" (deep comparison) в контексте оптимизации производительности React?](#что-такое-глубокое-сравнение-deep-comparison-в-контексте-оптимизации-производительности-react) |
| 42  | [Как использовать memoization для оптимизации компонентов?](#как-использовать-memoization-для-оптимизации-компонентов)                                                                               |

| 43 | [Какие паттерны использования Redux вы знаете?](#какие-паттерны-использования-redux-вы-знаете) |
| 44 | [Как работает библиотека React Router?](#как-работает-библиотека-react-router) |
| 45 | [Что такое SSR (Server-Side Rendering) и как он отличается от CSR (Client-Side Rendering)?](#что-такое-ssr-server-side-rendering-и-как-он-отличается-от-csr-client-side-rendering) |
| 46 | [Как реализовать асинхронную загрузку компонентов с помощью React Router?](#как-реализовать-асинхронную-загрузку-компонентов-с-помощью-react-router) |
| 47 | [Какие преимущества дает использование Redux для управления состоянием приложения?](#какие-преимущества-дает-использование-redux-для-управления-состоянием-приложения) |
| 48 | [Что такое Redux Thunk?](#что-такое-redux-thunk) |
| 49 | [Как работает Redux Saga?](#как-работает-redux-saga) |
| 50 | [Как реализовать ленивую загрузку Redux-редьюсеров?](#как-реализовать-ленивую-загрузку-redux-редьюсеров) |
| 51 | [Что такое "нормализация состояния" (state normalization) в контексте управления состоянием приложения?](#что-такое-нормализация-состояния-state-normalization-в-контексте-управления-состоянием-приложения) |
| 52 | [Как создать анимированный переход между страницами с помощью React Router?](#как-создать-анимированный-переход-между-страницами-с-помощью-react-router) |
| 53 | [Как работает CSS-модули (CSS Modules) в React?](#как-работает-css-модули-css-modules-в-react) |
| 54 | [Что такое Styled Components, и как оно используется?](#что-такое-styled-components-и-как-оно-используется) |
| 55 | [Как передать данные с сервера на клиент при использовании SSR в React?](#как-передать-данные-с-сервера-на-клиент-при-использовании-ssr-в-react) |
| 56 | [Какие преимущества и недостатки имеют функциональные компоненты по сравнению с компонентами классов?](#какие-преимущества-и-недостатки-имеют-функциональные-компоненты-по-сравнению-с-компонентами-классов) |
| 57 | [Какие особенности имеют хуки `useEffect` и `useLayoutEffect`?](#какие-особенности-имеют-хуки-useeffect-и-uselayouteffect) |
| 58 | [Как обновить состояние компонента после выполнения асинхронной операции?](#как-обновить-состояние-компонента-после-выполнения-асинхронной-операции) |
| 59 | [Что такое CSS-in-JS, и какие библиотеки вы знаете для реализации этой концепции в React?](#что-такое-css-in-js-и-какие-библиотеки-вы-знаете-для-реализации-этой-концепции-в-react) |
| 60 | [Как реализовать drag-and-drop функциональность в React-приложении?](#как-реализовать-drag-and-drop-функциональность-в-react-приложении) |

| 61 | [Что такое CSS Grid и как его использовать в React?](#что-такое-css-grid-и-как-его-использовать-в-react) |
| 62 | [Как реализовать аутентификацию и авторизацию в React-приложении?](#как-реализовать-аутентификацию-и-авторизацию-в-react-приложении) |
| 63 | [Как работает маршрутизация на стороне клиента в React?](#как-работает-маршрутизация-на-стороне-клиента-в-react) |
| 64 | [Что такое "code splitting" (разделение кода) в React?](#что-такое-code-splitting-разделение-кода-в-react) |
| 65 | [Как управлять состоянием между компонентами, не имеющими близкой связи?](#как-управлять-состоянием-между-компонентами-не-имеющими-близкой-связи) |
| 66 | [Какие средства предоставляет React для тестирования компонентов?](#какие-средства-предоставляет-react-для-тестирования-компонентов) |
| 67 | [Как работает "ленивая загрузка" (lazy loading) компонентов в React?](#как-работает-ленивая-загрузка-lazy-loading-компонентов-в-react) |
| 68 | [Что такое "синтетические события" (synthetic events) в React?](#что-такое-синтетические-события-synthetic-events-в-react) |
| 69 | [Как организовать переиспользование компонентов в React?](#как-организовать-переиспользование-компонентов-в-react) |
| 70 | [Что такое "высоконагруженные компоненты" (high-order components) и как их создать?](#что-такое-высоконагруженные-компоненты-high-order-components-и-как-их-создать) |
| 71 | [Какие принципы следует соблюдать при именовании компонентов в React?](#какие-принципы-следует-соблюдать-при-именовании-компонентов-в-react) |
| 72 | [Как реализовать анимацию переходов между компонентами в React Router?](#как-реализовать-анимацию-переходов-между-компонентами-в-react-router) |
| 73 | [Что такое "глубокий перенос состояния" (deep state transfer) в React?](#что-такое-глубокий-перенос-состояния-deep-state-transfer-в-react) |
| 74 | [Как реализовать модальное окно в React-приложении?](#как-реализовать-модальное-окно-в-react-приложении) |
| 75 | [Что такое SSR (Server-Side Rendering) и зачем его использовать?](#что-такое-ssr-server-side-rendering-и-зачем-его-использовать) |
| 76 | [Какие преимущества дает использование CSS-модулей (CSS Modules)?](#какие-преимущества-дает-использование-css-модулей-css-modules) |
| 77 | [Что такое "виртуальизация списка" (list virtualization) и как она реализуется в React?](#что-такое-виртуальизация-списка-list-virtualization-и-как-она-реализуется-в-react) |
| 78 | [Как реализовать инклуд компонентов в React?](#как-реализовать-инклуд-компонентов-в-react) |
| 79 | [Что такое "консилиация" (reconciliation) в контексте React?](#что-такое-консилиация-reconciliation-в-контексте-react) |
| 80 | [Как обрабатывать формы в React?](#как-обрабатывать-формы-в-react) |
| 81 | [Какие существуют альтернативы Redux для управления состоянием в React-приложениях?](#какие-существуют-альтернативы-redux-для-управления-состоянием-в-react-приложениях) |
| 82 | [Как работает "горячая замена модулей" (Hot Module Replacement) в среде разработки React-приложений?](#как-работает-горячая-замена-модулей-hot-module-replacement-в-среде-разработки-react-приложений) |
| 83 | [Что такое "мемоизация" (memoization) и как она может быть применена в React?](#что-такое-мемоизация-memoization-и-как-она-может-быть-применена-в-react) |
| 84 | [Как реализовать связывание данных (data binding) в React?](#как-реализовать-связывание-данных-data-binding-в-react) |
| 85 | [Что такое "передача данных через контекст" (context passing) в React?](#что-такое-передача-данных-через-контекст-context-passing-в-react) |
| 86 | [Как реализовать перетаскивание (drag-and-drop) элементов в React-приложении?](#как-реализовать-перетаскивание-drag-and-drop-элементов-в-react-приложении) |
| 87 | [Что такое "вычисляемые свойства" (computed properties) в контексте React?](#что-такое-вычисляемые-свойства-computed-properties-в-контексте-react) |
| 88 | [Какие методы жизненного цикла были убраны в React 16?](#какие-методы-жизненного-цикла-были-убраны-в-react-16) |
| 89 | [Как реализовать "ленивую загрузку" (lazy loading) изображений в React?](#как-реализовать-ленивую-загрузку-lazy-loading-изображений-в-react) |
| 90 | [Что такое "рендер-пропсы" (render props) и как они используются?](#что-такое-рендер-пропсы-render-props-и-как-они-используются) |
| 91 | [Как работает "ленивая загрузка" (lazy loading) сторонних библиотек в React?](#как-работает-ленивая-загрузка-lazy-loading-сторонних-библиотек-в-react) |
| 92 | [Что такое "реактивное программирование" (reactive programming) в контексте React?](#что-такое-реактивное-программирование-reactive-programming-в-контексте-react) |
| 93 | [Как обрабатывать ошибки при использовании хуков (hooks) в React?](#как-обрабатывать-ошибки-при-использовании-хуков-hooks-в-react) |
| 94 | [Что такое "инкапсуляция состояния" (state encapsulation) в React?](#что-такое-инкапсуляция-состояния-state-encapsulation-в-react) |
| 95 | [Как реализовать анимированный переход между компонентами в React Native?](#как-реализовать-анимированный-переход-между-компонентами-в-react-native) |
| 96 | [Что такое "стабильные идентификаторы" (stable keys) и зачем они нужны в React?](#что-такое-стабильные-идентификаторы-stable-keys-и-зачем-они-нужны-в-react) |
| 97 | [Как обновить состояние компонента после изменения props?](#как-обновить-состояние-компонента-после-изменения-props) |
| 98 | [Что такое "компоненты высшего порядка" (Higher-Order Components, HOC) в React?](#что-такое-компоненты-высшего-порядка-higher-order-components-hoc-в-react) |
| 99 | [Какие есть паттерны для работы с асинхронностью в React?](#какие-есть-паттерны-для-работы-с-асинхронностью-в-react) |
| 100 | [Что такое "реактивный поток данных" (reactive data flow) в контексте React?](#что-такое-реактивный-поток-данных-reactive-data-flow-в-контексте-react) |
