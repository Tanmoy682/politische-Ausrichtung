econ = 0
social = 0
migration_score = 0
green = 0
human_rights = 0
democracy = 0

# Wirtschaftsfragen
print("\nBesteuerung: Sollen hohe Einkommen und große Unternehmen progressiv besteuert werden, um öffentliche Dienstleistungen und den Sozialstaat zu finanzieren?\n"
      "1. Ja, progressive Steuern sollen stark in Wohlfahrt und Infrastruktur fließen.\n"
      "2. Steuern sollten Wohlfahrt, Wachstum und Wettbewerbsfähigkeit ausgleichen.\n"
      "3. Zu progressive Steuern schaden der Effizienz; Steuern sollten weniger progressiv sein.")
e1 = input("Deine Wahl (1-3): ")

print("\nWie stark sollte der Staat die Wirtschaft zentralisieren oder dezentralisieren?\n"
      "1. Der Staat sollte die meisten wichtigen Industrien kontrollieren und die Wirtschaft planen.\n"
      "2. Der Staat sollte wichtige Sektoren steuern, aber private Eigentumsrechte zulassen.\n"
      "3. Die Wirtschaft sollte hauptsächlich privat und mit minimaler staatlicher Kontrolle funktionieren.")
e2 = input("Deine Wahl (1-3): ")

# Sozialpolitik
print("\nWie sollte die Gesellschaft mit traditionellen Geschlechter- und Sozialrollen umgehen?\n"
      "1. Traditionelle kulturelle und religiöse Rollen sollten die gesellschaftliche Grundlage bleiben.\n"
      "2. Traditionen sollten respektiert werden, aber individuelle Freiheit ist erlaubt.\n"
      "3. Die Gesellschaft sollte sich zu flexibleren und sich entwickelnden Rollen bewegen.")
s1 = input("Deine Wahl (1-3): ")

print("\nSind Reformen zur Stärkung von Arbeitsrechten und zur Reduzierung von Diskriminierung notwendig?\n"
      "1. Soziale Hierarchien sind natürlich und sollten weitgehend bestehen bleiben.\n"
      "2. Diskriminierung sollte schrittweise reduziert werden, ohne soziale Stabilität zu gefährden.\n"
      "3. Starke Reformen sind notwendig, um Ungleichheit und Diskriminierung aktiv abzubauen.")
s2 = input("Deine Wahl (1-3): ")

print("\nWie sollte die Gesellschaft mit dem rechtlichen Status einer dritten Geschlechtsidentität umgehen?\n"
      "1. Es ist primär ein biologisches oder medizinisches Konzept und sollte traditionelle Normen nicht verändern.\n"
      "2. Es sollte rechtliche Anerkennung geben, aber im Einklang mit kulturellen Traditionen.\n"
      "3. Es sollte umfassende rechtliche Anerkennung und Selbstbestimmung geben.")
s3 = input("Deine Wahl (1-3): ")

# Migrationspolitik
print("\nWie beurteilst du Einwanderung in deinem Land?\n"
      "1. Zu viel Einwanderung kann kulturelle Identität schwächen und Ressourcen belasten.\n"
      "2. Einwanderung ist positiv, aber sollte kontrolliert und gut integriert werden.\n"
      "3. Einwanderung ist grundsätzlich positiv und stärkt Gesellschaften.")
m1 = input("Deine Wahl (1-3): ")

print("\nSollten Opfer von Gewalt das Recht auf Asyl haben?\n"
      "1. Asyl belastet die Gesellschaft zu stark und sollte stark eingeschränkt werden.\n"
      "2. Menschen in Gefahr sollten unter kontrollierten Bedingungen Asyl erhalten.\n"
      "3. Menschen sollten großzügigen Zugang zu Asyl und Schutz erhalten.")
m2 = input("Deine Wahl (1-3): ")

# Umweltpolitik
print("\nWelche Priorität sollte Umweltschutz in der Politik haben?\n"
      "1. Wirtschaftswachstum ist wichtiger als strenger Umweltschutz.\n"
      "2. Umwelt und Wirtschaft sollten ausgeglichen werden.\n"
      "3. Umweltschutz hat höchste Priorität, auch wenn Wachstum eingeschränkt wird.")
g1 = input("Deine Wahl (1-3): ")

print("\nWie sollte Umweltpolitik globale Ungleichheit berücksichtigen?\n"
      "1. Jedes Land sollte seine eigene Entwicklung priorisieren.\n"
      "2. Globale Auswirkungen sollten berücksichtigt werden, aber nationale Interessen bleiben wichtig.\n"
      "3. Umweltpolitik muss globale Gerechtigkeit und den Globalen Süden besonders berücksichtigen.")
g2 = input("Deine Wahl (1-3): ")

# Menschenrechte
print("\nWie sollten Menschenrechte in der Politik priorisiert werden?\n"
      "1. Sicherheit, Wirtschaft und Tradition sind wichtiger als Menschenrechte.\n"
      "2. Menschenrechte sind wichtig, aber Umsetzung hängt vom Kontext ab.\n"
      "3. Menschenrechte sind universell und gelten für alle gleich.")
h1 = input("Deine Wahl (1-3): ")

# Demokratie
print("\nWie sollte Meinungsfreiheit und politische Entscheidungsfindung organisiert sein?\n"
      "1. Autoritäres Modell: Einschränkung von Meinungsfreiheit für Stabilität.\n"
      "2. Technokratisches Modell: Experten treffen wichtige Entscheidungen.\n"
      "3. Liberale Demokratie: Freiheit, Wahlen und Pluralismus sind zentral.")
d1 = input("Deine Wahl (1-3): ")

#-----------------------Einstufung wirtschaftlich links/rechts-----------------------------------------

def fiscal_position(e1, e2):

    if e1 == "1" and e2 == "1":
        return "Wirtschaftlich: stark links / sozialistisch"

    elif e1 == "1" and e2 == "2":
        return "Wirtschaftlich: Mitte-links"

    elif e1 == "1" and e2 == "3":
        return "Sozialdemokratisch / umverteilende Marktwirtschaft"

    elif e1 == "2" and e2 == "1":
        return "Staatsorientierte Mischwirtschaft"

    elif e1 == "2" and e2 == "2":
        return "Wirtschaftlich: zentristisch"

    elif e1 == "2" and e2 == "3":
        return "Marktorientierter Zentrismus"

    elif e1 == "3" and e2 == "1":
        return "Staatskapitalismus"

    elif e1 == "3" and e2 == "2":
        return "Mitte-rechts Kapitalismus"

    elif e1 == "3" and e2 == "3":
        return "Freier Markt / libertärer Kapitalismus"
 
print("\nDeine politische Ausrichtung zusammengefasst!\n" \
"Deine wirtschaftliche Einordnung ist: " + fiscal_position(e1, e2))

#-----------------------soziale Einrichtung-----------------------------------------11
if s1 == "1":
    social -= 1
elif s1 == "2":
    social += 0
elif s1 == "3":
    social += 1

if s2 == "1":
    social -= 1
elif s2 == "2":
    social += 0
elif s2 == "3":
    social += 1

if s3 == "1":
    social -= 1
elif s3 == "2":
    social += 0
elif s3 == "3":
    social += 1

#------------------------Einstufung Migration----------------------------------------

if m1 == "1":
    migration_score -= 1
if m1 == "2":
    migration_score += 0
if m1 == "3":
    migration_score += 1

if m2 == "1":
    migration_score -= 1
if m2 == "2":
    migration_score += 0
if m2 == "3":
    migration_score += 1


total_social_migration_score = social + migration_score

if total_social_migration_score <= -2:
    print("Du bist gesellschaftlich stark traditionell / konservativ.\n")

elif total_social_migration_score == -1:
    print("Du bist gesellschaftlich konservativ.\n")

elif total_social_migration_score <= 1:
    print("Du bist gesellschaftlich zentristisch / moderat.\n")

elif total_social_migration_score == 2:
    print("Du bist gesellschaftlich progressiv.\n")

else:
    print("Du bist gesellschaftlich stark progressiv / libertär.\n")
    

#------------------------Einstufung Umwelt----------------------------------------

if g1 == "1":
    print("Du siehst den grünen Wandel nicht als politische Priorität.")

elif g1 == "2":
    print("Du siehst den grünen Wandel als wichtig, aber nicht als höchste Priorität.")

elif g1 == "3":
    print("Du siehst den grünen Wandel als höchste politische Priorität.")


if g2 == "1":
    print(
        "Deine Umweltpolitik ist eher national ausgerichtet und fokussiert auf Wirtschaftswachstum,\n"
        "mit weniger Fokus auf globale Umweltgerechtigkeit."
    )

elif g2 == "2":
    print(
        "Deine Umweltpolitik balanciert nationale Entwicklung und globale Umweltaspekte."
    )

elif g2 == "3":
    print(
        "Du glaubst, dass der grüne Wandel im eigenen Land nicht auf Kosten des Globalen Südens gehen darf."
    )


if g1 == "3" and g2 == "1":
    print(
        "Du unterstützt wahrscheinlich einen grün-nationalistischen Ansatz mit Fokus auf nationale Interessen."
    )

elif g1 == "3" and g2 == "3":
    print(
        "Du unterstützt wahrscheinlich Klimagerechtigkeit oder ökosozialistische Ansätze,\n"
        "bei denen der Wandel global gerecht gestaltet werden soll."
    )


#------------------------Einstufung Menschenrechte----------------------------------------

if h1 == "1":
    print("Du priorisierst nationale Sicherheit und kulturelle Traditionen\n"
          "über strikten Menschenrechtsschutz. Für dich ist das kompatibel, wenn es\n"
          "zu nationalen Interessen und Verbündeten passt.")

elif h1 == "2":
    print("Du glaubst, dass Menschenrechte grundsätzlich ein globaler Standard sein sollten,\n"
          "aber ihre Umsetzung hängt von Souveränität, Kultur und geopolitischen Faktoren ab.\n"
          "Diplomatie und Zusammenarbeit sind wichtiger als Zwang.")

elif h1 == "3":
    print("Du glaubst, dass universelle Menschenrechte für alle Menschen gleichermaßen gelten,\n"
          "unabhängig von nationalen Interessen oder Verbündeten.")
    

if g2 == "3" and h1 == "3":
    print("Du unterstützt wahrscheinlich einen kosmopolitischen Ansatz für Menschenrechte und Umweltpolitik,\n"
          "basierend auf globaler Gerechtigkeit und Zusammenarbeit.")

if g2 == "1" and h1 == "1":
    print("Deine globale Solidarität wirkt selektiv. Möglicherweise bestehen doppelte Standards :(\n")


#------------------------Einstufung Demokratie----------------------------------------

if d1 == "1":
    print("Du unterstützt ein autoritäres Modell mit Fokus auf Stabilität und Einheit,\n"
          "auch wenn dies Einschränkungen der Meinungsfreiheit bedeutet.")

elif d1 == "2":
    print("Du unterstützt ein technokratisches Modell, bei dem Experten viele Entscheidungen treffen,\n"
          "während Grundfreiheiten teilweise bestehen bleiben.")

elif d1 == "3":
    print("Du unterstützt eine liberale Demokratie mit Meinungsfreiheit, Wahlen und starken Bürgerrechten.")

# ---------------- Ergebnis ----------------

democratic_socialist = 0
libertarian = 0
national_conservative = 0
authoritarian_socialist = 0
eco_socialist = 0
centrist = 0
liberal_democrat = 0

# (Restliche Logik bleibt exakt gleich – nur Ausgabe geändert)

# ---------------- Demokratischer Sozialismus ----------------
if e1 == "1":
    democratic_socialist += 2

if e2 == "1" or e2 == "2":
    democratic_socialist += 2

if s1 == "3":
    democratic_socialist += 1

if s2 == "3":
    democratic_socialist += 2

if s3 == "3":
    democratic_socialist += 1

if m1 == "3":
    democratic_socialist += 1

if m2 == "3":
    democratic_socialist += 1

if g1 == "3":
    democratic_socialist += 1

if g2 == "3":
    democratic_socialist += 1

if h1 == "3":
    democratic_socialist += 1

if d1 == "3":
    democratic_socialist += 1


# ---------------- Libertarismus ----------------
if e1 == "3":
    libertarian += 2

if e2 == "3":
    libertarian += 2

if s1 == "3":
    libertarian += 1

if s2 == "3":
    libertarian += 1

if s3 == "3":
    libertarian += 1

if m1 == "3":
    libertarian += 1

if d1 == "3":
    libertarian += 2


# ---------------- Nationalkonservativ ----------------
if e1 == "2" or e1 == "3":
    national_conservative += 1

if e2 == "3":
    national_conservative += 2

if s1 == "1":
    national_conservative += 2

if s2 == "1":
    national_conservative += 2

if s3 == "1":
    national_conservative += 2

if m1 == "1":
    national_conservative += 2

if m2 == "1":
    national_conservative += 1

if g1 == "1" or g1 == "2":
    national_conservative += 1

if d1 == "1":
    national_conservative += 2


# ---------------- Autoritärer Sozialismus ----------------
if e1 == "1":
    authoritarian_socialist += 2

if e2 == "1":
    authoritarian_socialist += 2

if s1 == "1" or s1 == "2":
    authoritarian_socialist += 1

if m1 == "1":
    authoritarian_socialist += 1

if d1 == "1":
    authoritarian_socialist += 3

if h1 == "1":
    authoritarian_socialist += 2


# ---------------- Ökosozialismus ----------------
if e1 == "1" or e1 == "2":
    eco_socialist += 1

if s2 == "3":
    eco_socialist += 1

if s3 == "3":
    eco_socialist += 1

if g1 == "3":
    eco_socialist += 3

if g2 == "3":
    eco_socialist += 3

if h1 == "3":
    eco_socialist += 1

if d1 == "3":
    eco_socialist += 1


# ---------------- Zentrismus ----------------
if e1 == "2":
    centrist += 2

if e2 == "2":
    centrist += 2

if s1 == "2":
    centrist += 1

if s2 == "2":
    centrist += 1

if s3 == "2":
    centrist += 1

if m1 == "2":
    centrist += 1

if m2 == "2":
    centrist += 1

if g1 == "2":
    centrist += 1

if g2 == "2":
    centrist += 1

if h1 == "2":
    centrist += 1

if d1 == "2":
    centrist += 2


# ---------------- Liberale Demokratie ----------------
if e1 == "2" or e1 == "1":
    liberal_democrat += 1

if e2 == "2" or e2 == "3":
    liberal_democrat += 1

if s1 == "3":
    liberal_democrat += 1

if s2 == "3":
    liberal_democrat += 1

if s3 == "3":
    liberal_democrat += 1

if m1 == "2" or m1 == "3":
    liberal_democrat += 1

if m2 == "2" or m2 == "3":
    liberal_democrat += 1

if h1 == "3":
    liberal_democrat += 2

if d1 == "3":
    liberal_democrat += 3


# ---------------- Endergebnis ----------------

# Finale Ausgabe
results = {
    "Demokratischer Sozialismus": democratic_socialist,
    "Libertarismus": libertarian,
    "Nationalkonservativ": national_conservative,
    "Autoritärer Sozialismus": authoritarian_socialist,
    "Ökosozialismus": eco_socialist,
    "Zentristisch": centrist,
    "Liberaler Demokrat": liberal_democrat
}

highest = max(results, key=results.get)

print("\n---------------- FINALES ERGEBNIS ----------------")
print("Du passt am besten zu:", highest)
