# Radmor_5100_5102_tuning
Radmor 5100 5102 TE tuning modyfikacja modułu tunera toru AM Program Pierwszy Polskiego Radia 225kHz

Amplitunery firmy Unitra Radmor 5100 5102 (TE) są wyposażone w moduł tunera AM przestrajany elektronicznie za pomocą diod pojemnosciowych (varicap). Współdzielą one 8-mio pozycyjny programator z tunerem FM. Powoduje to że z w praktyce tuner AM nie jest wykorzystywany ponieważ 8 pozycji to za mało dla tunera FM i nikt nie rezygnuje ze stacji FM na rzecz AM. W Polsce obecnie (lipiec 2024) pracuje jeden nadajnik AM który emituje Program Pierwszy Polskiego Radia na częstotliwości 225kHz. Proponowana modyfikacja przewiduje dostrojenie na stałe tunera AM do częstotliowści 225kHz. Dzięki temu wybranie pozycji AM na selektorze tunera powoduje z automatu odbiór tej stacji, bez angażowania programatora. 

W celu przeprowadzenia modyfikacji należy:
- wylutowac elementy wyróznione na rysunku radmor_5102_tuner_am.png, stan po modyfikacji został przedstawiony na rysunku radmor_5102_tuner_am_po_przerobce.png
- wymienić dwa kondenastory ceramiczne (C2, C9) na 82pF
- po ostygnieciu modułu do temperatury pracy urządzenia stroimy kondensatory nastawne (C5, C6) na częstotliowść 225kHz i na maksimum sygnału

Ta modyfikacja została przetestowana przez autora i jest stabilna na przestrzeni kilku lat (moduł nie odstraja się).
