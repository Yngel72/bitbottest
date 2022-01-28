### @activities true

# Programmer bitboten til å kjøre
## Introduksjon
### Introduksjon @unplugged

Lær hvordan du får BitBoten til å kjøre

### Steg 1

Aller først må du fortelle programmet hvilken versjon av BitBot du har. Hent en ``||Bitbot.select BitBot model||``-blokk fra ``||Bitbot.BitBot/BitBot model||`` menyen og dra den inn i gapet på ``||Basic.on start||``-blokka.
```blocks
bitbot.select_model(BBModel.Classic)
```
```package
bitbot=github:4tronix/BitBot
```
