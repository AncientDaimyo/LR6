Лабораторная работа №6
Ход работы

У меня уже был аккаунт на GitHub, поэтому регистрироваться не пришлось. Я сделал копию исходного репозитория к себе. Первым делом настроил Git введя параметры git config --global user.name <username> и git config --global user.email <email>. Затем с помощью git clone <url> загрузил репозиторий.
  
![Screenshot 2021-11-19 211610](https://user-images.githubusercontent.com/71555809/142687529-e20973a8-d9f3-47b0-a2ca-1ff1d23c87af.png)

![Screenshot 2021-11-19 211933](https://user-images.githubusercontent.com/71555809/142687575-6e63dd7e-9b0d-460f-b277-4f37e3ee8bee.png)


После этого добавил в ветку новый файл и закоммитил его.
  
![изображение](https://user-images.githubusercontent.com/71555809/142687845-a04a0a3a-d9fe-4623-97f1-4df38f3829f0.png)

![изображение](https://user-images.githubusercontent.com/71555809/142687865-647bd1b5-e5e7-4cbb-86ef-0fb6eda6a257.png)

Далее с помощью команда git log запрашиваем историю изменений ветки, а с помощью git checkout <name> переключаемся между ветками

![изображение](https://user-images.githubusercontent.com/71555809/142687917-a21b694e-8a0b-40fd-a22b-0bcb2bf78e02.png)

Далее пытаемся слить ветку branch1 в master командой git merge branch1. Проблему слияния решил с помощью mergetool.
  
![изображение](https://user-images.githubusercontent.com/71555809/142688171-4026153a-5198-460d-bcbd-f7dec1c6333f.png)
И конечно коммит.
![изображение](https://user-images.githubusercontent.com/71555809/142688213-2a42edf4-715b-4273-88be-832cb88cc564.png)
  ![изображение](https://user-images.githubusercontent.com/71555809/142688284-464a4174-f88a-4c26-a772-ee0d1e49062e.png)


  После чего была выполнена команда git add * и сделан коммит. 
  ![изображение](https://user-images.githubusercontent.com/71555809/142688359-f1ec7189-9430-4875-88f8-e9cc0c450a71.png)


Затем был произведене хард откат git reset --hard <name>

![изображение](https://user-images.githubusercontent.com/71555809/142688383-9db557d3-8fb2-4afd-b02f-7f57bd248311.png)



После чего создал ветку репорт и начал делать отчет.
  ![изображение](https://user-images.githubusercontent.com/71555809/142688587-dc434b7d-f5f7-4d86-8e0e-3e2f62a79d87.png)
Пришлось запушить изменения, чтобы ветка появилась.
  ![изображение](https://user-images.githubusercontent.com/71555809/142688682-c82509ec-a03f-43ae-93e8-3fef7a614fb3.png)
Затем я удалил ветку branch1.
  ![изображение](https://user-images.githubusercontent.com/71555809/142688779-5e0e936a-6374-4024-9744-446d7e5b3de8.png)


После чего запросил логи в кратком формате "сокращённый хэш + дата + имя автора + комментарий"

![изображение](https://user-images.githubusercontent.com/71555809/142688842-69d8f478-89b0-4ef5-bb62-3cf2fbf7e808.png)

Закончил отчет и на всякий случай запушил ещё раз
  ![изображение](https://user-images.githubusercontent.com/71555809/142688983-dcfada3f-ce4e-4ff0-aa1f-f55bf1ba8a98.png)
