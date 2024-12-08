<template>
    <div v-if="show" class="modal-shadow" @click.self="closeModal">
        <div class="modal">
            <div class="modal-close" @click="closeModal">&#10006;</div>
            <slot name="title">
                <h3 class="modal-title">{{ title }}</h3>
            </slot>
            <slot name="content">
                <div class="modal-content" v-if="title === 'Лицензионное соглашение'">
                    <text>Lorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conseLorem ipsum dolor sit amet conse</text>
                </div>
                <div class="modal-content" v-if="title === 'Политика конфиденциальности'">
                    <text>
1. Введение/n
Настоящая Политика конфиденциальности (далее — «Политика») определяет, как [Название Компании] (далее — «Компания») собирает, использует и защищает личную информацию пользователей мобильного приложения [Название Приложения] (далее — «Приложение»).
2. Сбор личной информации
2.1. Компания собирает следующую личную информацию:
Имя и фамилия
Адрес электронной почты
Номер телефона
Местоположение (при использовании функций, требующих геолокации)
Данные о поведении пользователя в Приложении (например, история просмотров, покупок)
2.2. Личная информация собирается только с согласия пользователя, за исключением случаев, когда это необходимо для предоставления услуг или выполнения договорных обязательств.
3. Использование личной информации
3.1. Компания использует личную информацию для следующих целей:
Улучшение качества обслуживания
Персонализация контента и предложений
Анализ поведения пользователей для улучшения функционала Приложения
Отправка уведомлений и обновлений
3.2. Компания не продает личную информацию третьим лицам.
4. Защита личной информации
4.1. Компания принимает все необходимые меры для защиты личной информации от несанкционированного доступа, использования и раскрытия.
4.2. Личная информация хранится на защищенных серверах и передается по зашифрованным каналам связи.
5. Права пользователей
5.1. Пользователи имеют право на доступ к своей личной информации, ее исправление и удаление.
5.2. Пользователи могут запросить ограничение или прекращение обработки их личной информации в любое время.
6. Изменения в Политике конфиденциальности
6.1. Компания оставляет за собой право вносить изменения в настоящую Политику конфиденциальности.
6.2. Все изменения будут опубликованы на этой странице, и пользователи могут в любой момент ознакомиться с актуальной версией Политики.
7. Контакты
7.1. Если у вас возникли вопросы или предложения по поводу настоящей Политики конфиденциальности, вы можете связаться с нами по адресу:
Электронная почта: [email@example.com]
Телефон: [номер телефона]
Мы благодарим вас за использование нашего Приложения и ценим ваше доверие.</text>
                </div>
            </slot>
            <slot name="footer">
                <div class="modal-footer">
                    <button class="modal-footer_button" @click="closeModal">
                        Ок
                    </button>
                </div>
            </slot>
        </div>
    </div>
</template>
 
<script>
    export default {
        name: "ModalWindow",
        data: function () {
            return {
                title: "Заголовок",
                show: false
            }
        },
        methods: {
            closeModal: function () {
                this.show = false

            },
            openModal: function (title) {
                this.show = true;
                this.title = title;
            }
        }
    }
</script>
 
<style scoped>
    .modal-shadow {
        position: fixed;
        top: 0;
        left: 0;
        min-height: 100%;
        width: 100%;
        background: rgba(0, 0, 0, 0.39);
    }
 
    .modal {
        background: #fff;
        border-radius: 8px;
        padding: 15px;
        min-width: 420px;
        max-width: 50%px;
        max-height: 90%;
        position: fixed;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    .modal-close {
        border-radius: 50%;
        color: #fff;
        background: #000000;
        display: flex;
        align-items: center;
        justify-content: center;
        position: absolute;
        top: 7px;
        right: 7px;
        width: 30px;
        height: 30px;
        cursor: pointer;
    }
 
    .modal-title {
        color: #000000;
    }
 
    .modal-content {
        margin-bottom: 20px;
        overflow: scroll;
        color: rgb(0, 0, 0);
        max-height: 70vh;
    }
 
    .modal-footer {
        &__button {
            background-color: #0971c7;
            color: #fff;
            border: none;
            text-align: center;
            padding: 8px;
            font-size: 17px;
            font-weight: 500;
            border-radius: 8px;
            min-width: 150px;
        }
    }
</style>