# TreeView
## Specyfikacja aplikacji
Aplikacja służy do tworzenia i zarządzania strukturą drzewiastą.

### Funkcjonalności:
  1. Tworzenie węzłów (węzły można dodawać jako korzenie bądź dzieci innych węzłów).
  2. Usuwanie węzłów.
  3. Edycja węzłów.
  4. Przenoszenie węzłów do innej lokalizacji.
  5. Sortowanie węzłów.
  6. Rozwijanie i zwijanie całej struktury.

### Interfejs aplikacji:
  <details>
    <summary>Ekran główny</summary>
    <img width="888" alt="main" src="https://user-images.githubusercontent.com/79647437/173398115-50a5aadd-4c4a-4e49-a634-aaf68babec57.PNG">
  </details>
  
  <details>
    <summary>Okno dodawania węzła</summary>
    <img width="521" alt="add_node" src="https://user-images.githubusercontent.com/79647437/173398840-20c87c79-6096-433b-934b-eb675ac23ce3.PNG">
  </details>
  
  <details>
    <summary>Okno usuwania węzła</summary>
    <img width="461" alt="delete_node" src="https://user-images.githubusercontent.com/79647437/173398907-f3d804b4-4cca-4414-b66b-931e3935201e.PNG">
  </details>
  
  <details>
    <summary>Okno edycji węzła</summary>
    <img width="425" alt="update_node" src="https://user-images.githubusercontent.com/79647437/173399107-7aee84ed-900b-4678-a2b1-5ac62f4055ce.PNG">
  </details>
  
  <details>
    <summary>Okno przenoszenia węzła</summary>
    <img width="440" alt="move_node" src="https://user-images.githubusercontent.com/79647437/173399233-4dfbf9a1-4cf5-450d-a3c2-35dbfd9056c5.PNG">
  </details>
  
  <details>
    <summary>Okno sortowania węzłów</summary>
    <img width="528" alt="sort" src="https://user-images.githubusercontent.com/79647437/173399315-6d65b800-d963-4af2-a32b-dcd5ccba321e.PNG">
  </details>
  
 W oknach zarządzania węzłami zastosowane są pola typu "select" z wyszukiwaniem.

## Wykorzystane technologie
Bootstrap, HTML, CSS, JavaScript, Laravel

## Wykorzystane narzędzia do zarządzania bazą danych
phpMyAdmin

<details>
    <summary>Tabela przechowująca dane na temat węzłów</summary>
    <img width="393" alt="database" src="https://user-images.githubusercontent.com/79647437/173400613-ea361942-705c-48b5-bd76-0db95c1c39b5.PNG">

  </details>
 
## Dane dotyczące bazy danych:
host = localhost
user = root
password = ''
database_name = treedatastructure

