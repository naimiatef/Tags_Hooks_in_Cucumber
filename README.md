# Tags_Hooks_in_Cucumber
## l'architecture de notre projet:
![image](https://user-images.githubusercontent.com/7100940/213880809-1ba74465-f426-4c2c-a159-a1c2ab44b390.png)

## le fichier Scenario.feature
![image](https://user-images.githubusercontent.com/7100940/213880855-28209e64-d4bd-4525-b9fb-a87fbcd87d3f.png)

## le fichier Step.java
![image](https://user-images.githubusercontent.com/7100940/213880892-bb327511-0c9f-4d5e-b76c-bda37151f896.png)

## le fichier Hooks.java
![image](https://user-images.githubusercontent.com/7100940/213880945-b5a9d1f2-60f2-4e12-966b-ffb9659fa167.png)


## Remarque: 
- Nous avons appris que les Hooks @Before et @After s’exécutent avant et après chaque scénario. Mais @Before(« @First ») ne fonctionnera qu’avant le premier scénario et les autres  tagged hooks. Encore une fois, ces noms de Taggs peuvent être n’importe quoi et pas besoin d’être premier, deuxième et troisième.

## Sortie
![image](https://user-images.githubusercontent.com/7100940/213881139-78461cef-3ca8-46d1-8c4c-43e8ed835638.png)
