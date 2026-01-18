einkaufsliste = []
entscheidung = "y"

while entscheidung == "y":
    einkaufsliste.append(input("Was möchtest du deiner Liste hinzufügen? "))
    entscheidung = input("Möchtest du weitere Artikel hinzufügen (y/n): ")
    print(einkaufsliste)

while True:
    aktion = input(
        "Möchtest du einen Artikel hinzufügen, entfernen oder die Liste anzeigen? "
        "(hinzufügen / entfernen / anzeigen / beenden): "
    )

    if aktion == "hinzufügen":
        artikel = input("Welchen Artikel möchtest du hinzufügen? ")
        einkaufsliste.append(artikel)
        print("Artikel wurde hinzugefügt")

    elif aktion == "entfernen":
        artikel = input("Welchen Artikel möchtest du entfernen? ")

        if artikel in einkaufsliste:
            einkaufsliste.remove(artikel)
            print("Artikel wurde gelöscht")
        else:
            print("Den Artikel gibt es nicht!")

    elif aktion == "anzeigen":
        print("Deine Einkaufsliste:")
        print(einkaufsliste)

    elif aktion == "beenden":
        print("Einkaufsliste beendet.")
        print("Deine finale Einkaufsliste:")
        for artikel in einkaufsliste:
            print("-", artikel)
        break

    else:
        print("Ungültige Eingabe!")
