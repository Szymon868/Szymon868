
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Strona z ramkami</title>
    <style>
        ul {
            list-style-position: inside; /* Ustawia kropki bliżej treści */
            padding-left: 0; /* Usuwa domyślny odstęp od lewej */
            margin-left: 0; /* Usuwa domyślny margines od lewej */
        }
        li {
            margin-bottom: 5px; /* Dodaje niewielki odstęp między elementami listy */
        }
        .header-footer {
            text-align: center;
            font-family: 'Georgia', serif; /* Elegancka czcionka */
            font-weight: bold;
        }
        .header-footer .title {
            font-size: 24px; /* Duży rozmiar dla nazwiska */
            letter-spacing: 2px; /* Dodaje odstępy między literami */
        }
        .header-footer .subtitle {
            font-size: 16px; /* Mniejszy rozmiar dla daty */
            font-style: italic; /* Kursywa dla daty */
            margin-top: 5px; /* Odstęp od nazwiska */
        }
    </style>
</head>
<body>
<table width="95%" border="1" align="center">
    <!-- Nagłówek -->
    <tr>
        <td colspan="3" class="header-footer">
            <div class="title">Chyliński</div>
            <div class="subtitle">Gdańsk, 22.11.2024</div>
        </td>
    </tr>
    <!-- Środek strony -->
    <tr>
        <!-- Lewe menu -->
        <td width="18%" align="center">
            <b>Lewe menu</b>
            <ul>
                <li><a href="https://zse.edu.gdansk.pl/" target="obszar_glowny">Strona ZSE</a></li>
                <li><a href="https://www.kuratorium.gda.pl/" target="obszar_glowny">Kuratorium</a></li>
            </ul>
        </td>
        <!-- Obszar główny -->
        <td align="center">
            <iframe width="650" height="420" name="obszar_glowny" src="start.html" border="0"></iframe>
            <b>Obszar główny</b>
        </td>
        <!-- Prawe menu -->
        <td width="18%" align="center">
            <b>Prawe menu</b>
            <ul>
                <li><a href="?-plik" target="obszar_glowny">Kliknij, aby ściągnąć plik</a></li>
                <li><a href="?-plik" target="obszar_glowny">Kliknij, aby zobaczyć tabelę</a></li>
                <li><a href="file:///D:/winryny%20i%20aplikacje%20internetowe/formularzindex.html" target="obszar_glowny">Kliknij, aby zobaczyć formularz</a></li>
                <li><a href="mailto:?-mail">Kliknij, aby wysłać pocztę</a></li>
                <li><a href="file:///C:/Users/dell/Desktop/g%C5%82ownyindex.html" target="obszar_glowny">Zadania od Z1 do Z6</a></li>
            </ul>
        </td>
    </tr>
    <!-- Stopka -->
    <tr>
        <td colspan="3" class="header-footer">
            <div class="title">Chyliński</div>
            <div class="subtitle">Gdańsk, 22.11.2024</div>
        </td>
    </tr>
</table>
</body>
</html>
