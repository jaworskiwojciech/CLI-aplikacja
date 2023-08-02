# CLI-aplikacja

# Otrzymujemy listę kontaktów

node index.js --action list
![Wynik w konsoli](/images/action-list.jpg)

# Otrzymujemy kontakt po id

node index.js --action get --id C9sjBfCo4UJCWjzBnOtxl
![Wynik w konsoli](/images/action-get.jpg)

# Dodajemy kontakt

node index.js --action add --name Harry Potter --email harrypotter@hogwarts.com --phone 123-45-68
![Wynik w konsoli](/images/action-add.jpg)

# Usuwamy kontakt

node index.js --action remove --id C9sjBfCo4UJCWjzBnOtxl
![Wynik w konsoli](/images/action-remove.jpg)
