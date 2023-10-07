ImGui 1.0
========================
- Udało się tworzyć nowe checkBoxy i żeby były one od siebie niezależne. 
- - Warunek? : Nazwa "label" musi być różna, gdyż to ona inaczej mówiąc odpowiada za ID checkBoxa.

Pomysł
==========
- Dobrym pomysłem, może być tworzenie losowego id przez nas samych, a zamiast używać "label" jako tekstu to wstawiali byśmy "ImGui::InputTextMultiline". Warunek? Należy dodać do naszej klasy dodatkową zmienną "id", wraz z metodą jej tworzenia no i obrobić to tak aby tworzyło nam te pole tekstowe wraz z checkBoxem, plus ewentualne dodatkowe zmiany w postaci "skreślania" tekstu jeśli chceckBox jest odhaczony.

Aktualny działający kod!
----
```
if(ImGui::Begin("TEST", &show_another_window))
        { 
            ImGui::InputText("Tekst",&str);
            if(ImGui::Button("Label"))
            {
                klasy.push_back(Klasa(str, false));
            }
            
            for(auto &t : klasy)
            {
                   ImGui::Checkbox(t.task.c_str(), &t.done); 
            }

            ImGui::End();
        }
```







