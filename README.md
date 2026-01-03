# projekt-ne-vegla

# Menaxhimi i Studentëve

Ky projekt është një program i thjeshtë në C++ për menaxhimin e studentëve. Ai lejon regjistrimin, shfaqjen, kërkimin dhe fshirjen e studentëve nga një listë. Projektuar për përdorim edukativ dhe për mësim mbi strukturat dhe funksionet në C++.

## Karakteristikat Kryesore
- Ruajtja e të dhënave të studentëve në një `vector` të strukturave `Student`.
- Shfaqja e listës së studentëve
- Kërkimi i studentëve sipas emrit.
- Fshirja e studentëve sipas ID-së.
- Kontroll i thjeshtë për raste kur lista është bosh ose studentët nuk gjenden.

## Struktura e Projektit
- `main.cpp` – File kryesor që përmban logjikën e programit.
- Funksione të ndara për shfaqje, kërkim dhe fshirje të studentëve:
  - `shfaqStudentet` – shfaq të gjithë studentët e regjistruar.
  - `kerkoSipasEmrit` – kërkon studentin me emrin e dhënë.
  - `fshiStudent` – fshin studentin me ID të specifikuar.
