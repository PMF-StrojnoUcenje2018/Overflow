# StrojnoUcenje

Ovo je repozitorij napravljen za projekt iz kolegija Strojno učenje s temom Sudbina životinja u skloništima.

Zadatak je preuzet s Kaggle-a, a naše se rješenje sastoji od 4 Jupyter Notebook datoteka. Prije pokretanja bilo koje od tih datoteka, 
potrebno je sa stranice natjecanja (https://www.kaggle.com/c/shelter-animal-outcomes) preuzeti train i test skupove podataka te ih 
spremiti u poddirektorij data.

Datoteka data_cleanup.ipynb služi za čišćenje i pripremu podataka za model. Prilagođena je i za train i test set.
Datoteke xgboost_model.ipynb, randomforest_model.ipynb i SVM.ipynb sadrže istoimene metode za multiklasifikaciju.
Nakon čišćenja podataka, moguće je pokrenuti željenu metodu i dobiti klasifikaciju za test set.

U poddirektoriju data nalaze se već pripremljeni podatci koji se mogu iskoristiti u svrhu učenja i treniranja modela.

Datoteka pocetna_analiza.ipynb sadrži analizu ponekih svojstava iz početnog train seta.

U radu smo najviše koristili biblioteke pandas, numpy, sklearn, xgboost i matplotlib. Biblioteka pandas poslužila nam je za rukovanje
podatcima, numpy kao pomoć pandasu, sklearn sadrži sve metode koje smo koristili za multiklasifikaciju, osim metode
XGBoost, koja je sadržana u xgboost. Biblioteka matplotlib najviše nam je poslužila za vizualizaciju podataka u pocetna_analiza.ipynb. 
