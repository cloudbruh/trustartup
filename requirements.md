# Функциональные требования

1. Система должна позволять регистрацию новых пользователей
2. Система должна производить авторизацию пользователей по логину и паролю
3. Система должна выдавать пользователям роли в зависимости от предоставленных персональных данных и результатов их проверки.
4. Система должна предоставлять пользователям с ролью `Стартапер` возможность создания стартапов на платформе.
5. Основатель стартапа должен иметь возможность после регистрации стартапа на платформе публиковать на странице стартапа важные события.
6. Система должна показывать на главной странице ленту с карточками зарегистрированных на платформе стартапов
7. Cистема должна предоставлять пользователю доступ к странице стартапа, с указанием названия, краткого описания, бизнес-плана, объеме собранных на платформе пожертвований, нанятых на платформе сотрудников, новостей стартапа.
8. Для всех зарегистрированных пользователей должна быть возможность жертвовать денежные средства в зарегистрированные на платформе стартапы, а также оставлять лайки и писать комментарии.
9. Для пользователей с ролью `Соискатель` на странице стартапа должна быть возможность оставить заявку на работу в стартапе
10. У работодателя должна быть возможность принимать или отклонять заявки Соискателей в свои стартапы. При принятии заявки новый сотрудник должен отображаться на странице стартапа.
11. У трудоустроившихся на платформе Соискателей и их работодателей должна быть возможность выставлять друг другу оценки и писать друг о друге комментарии, которые должны отображаться на соответствующих страницах.
12. Система должна информировать Стартаперов о том, кто и какой объем средств пожертвовал в стартап.
13. Система должна позволять пользователям с ролью `Модератор` имеют доступ к специальному интерфейсу модерации данных.
14. Система должна позволять Модераторам проверять введенные пользователям персональные данные перед одобрением повышения роли пользователя.
15. Система должна позволять Модераторам перед одобрение регистрации стартапа проверять введенные Стартапером данные.

# Нефункциональные требования

1. Новая учетная запись пользователя должна быть создана менее чем за 2000 мс
2. Система должна иметь не менее 99% доступности
3. Система должна обслуживать до 1000 одновременных пользователей
4. Система должна быть горизонтально масштабируемой для увеличения числа одновременных пользователей
5. Пользователь должен иметь возможность перейти на любую страницу сайта не более чем за 3 клика
