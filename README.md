# Laravel 12 für Anfänger – Der pragmatische Einstieg

![Laravel 12 Book Cover](./path/to/your/cover-image.jpg) 
*(Hinweis: Hier das Mockup-Bild verlinken, das wir erstellt haben!)*

Willkommen im offiziellen Repository zum Buch **"Laravel 12 für Anfänger"**. 
Dieses Repository enthält nicht nur Code-Schnipsel, sondern vollständig ausprogrammierte Beispiel-Anwendungen, die dich von "Hello World" zur produktionsreifen App führen.

## 🚀 Über dieses Projekt

Webentwicklung wirkt heute oft unnötig komplex. Dieses Buch (und dieser Code) tritt an, um das zu ändern. Wir nutzen das modernste Tooling (**Laravel 12**, **Herd**, **Vite**), um ohne unnötigen Ballast professionelle Web-Apps zu bauen.

**Was dich hier erwartet:**
* **Kein Spaghetti-Code:** Sauber strukturierte MVC-Architektur.
* **Moderner Stack:** Nutzung von Laravel Herd & Vite statt veralteter Setups.
* **Best Practices:** Sicherheit, Validierung und Eloquent ORM korrekt angewendet.

---

## 📂 Die Projekte aus dem Buch

Der Code ist in logische Abschnitte unterteilt, die den Kapiteln im Buch entsprechen:

| Kapitel | Projekt | Beschreibung | Tech-Fokus |
| :--- | :--- | :--- | :--- |
| **Kap. 04** | 🧮 **Der Taschenrechner** | Deine erste Route & Controller-Logik. | Routing, Blade Basics |
| **Kap. 06** | ✅ **Task-Manager** | Eine komplette To-Do App mit Datenbank. | Migrations, Eloquent, CRUD |
| **Kap. 09** | 🔌 **REST API** | Eine Schnittstelle für externe Apps. | API Resources, Sanctum Auth |
| **Kap. 10** | 🛒 **Der Mini-Shop** | Das große Abschlussprojekt. | Warenkorb, Checkout, Middleware |

---

## 🛠 Installation & Setup

Du willst den Code direkt ausprobieren? Folge diesen Schritten (optimiert für Laravel Herd):

1.  **Repository klonen:**
    ```bash
    git clone [https://github.com/MichaelThielen/Laravel-12-Buch.git](https://github.com/MichaelThielen/Laravel-12-Buch.git)
    cd laravel-12-buch
    ```

2.  **Abhängigkeiten installieren:**
    ```bash
    composer install
    npm install
    ```

3.  **Environment einrichten:**
    ```bash
    cp .env.example .env
    php artisan key:generate
    ```

4.  **Datenbank migrieren (SQLite/MySQL):**
    ```bash
    php artisan migrate --seed
    ```

5.  **Server starten (falls nicht über Herd):**
    ```bash
    npm run dev
    php artisan serve
    ```

---

## 💡 Warum dieser Code anders ist

Viele Tutorials zeigen dir den "schnellen Weg". Dieser Code zeigt dir den **richtigen Weg**.
Als Entwickler, der seit **1984** dabei ist, habe ich gelernt: *Technische Schulden* sind die teuersten Schulden, die man machen kann. Deshalb findest du hier:
* ✅ Strikte Typisierung (wo sinnvoll).
* ✅ Form Requests zur Validierung (statt Logik im Controller).
* ✅ Blade Components für wiederverwendbares UI.

---

## 📚 Das Buch kaufen

Gefällt dir der Code? Das komplette Wissen dahinter – *das "Warum"* und nicht nur *das "Wie"* – findest du im Buch.


---

## 👨‍💻 Über den Autor

**Michael Thielen** entwickelt seit vier Jahrzehnten Software. Er hat die Ära der Lochkarten knapp verpasst, aber alles danach mitgemacht. Heute hilft er Einsteigern, den Nebel der modernen Webentwicklung zu lichten und den Spaß am Coden zurückzugewinnen.

* (https://www.linkedin.com/in/michael-thielen-563057204

---

MIT License. Viel Erfolg beim Coden!
