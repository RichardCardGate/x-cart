![CardGate](https://cdn.curopayments.net/thumb/200/logos/cardgate.png)

# CardGate module für X-Cart

[![Build Status](https://travis-ci.org/cardgate/x-cart.svg?branch=master)](https://travis-ci.org/cardgate/x-cart)

## Support

Dieses Modul is geeignet für X-Cart Version **4.4.0** bis zum Version **4.7.x**

## Vorbereitung

Um dieses Modul zu verwenden, sind Zugangsdaten zu **CardGate** notwendig.  
Gehen Sie zu [**Mein CardGate**](https://my.cardgate.com/) und fragen Sie Ihre **Site ID** und **Hash Key** an, oder kontaktieren Sie Ihren Accountmanager.

## Installation

1. Downloaden und entpacken Sie den aktuellsten [**cardgate.zip**](https://github.com/cardgate/x-cart/releases) Datei auf Ihrem Desktop.

2. Uploaden Sie den **install_cardgateplus-Ordner**, den **include-Ordener** und den **payment-Ordner** in den **root-Ordner** Ihres Webshops. 

3. Öffnen Sie **http://meinwebshop.com/install_cardgateplus** in Ihrem Browser und installieren Sie das Plugin.  
   (Tauschen Sie **http://meinwebshop.com** mit der URL Ihres Webshops aus.)  
   
4. Entfernen Sie aus Sicherheitsgründen den **install_cardgateplus** Ordner von Ihrem Webshop.

## Konfiguration

1. Loggen Sie sich in den **Adminbereich** Ihres Webshops ein.

2. Klicken Sie auf den Tab **Einstellungen** und wählen Sie **Zahlungsmittel** aus.

3. Klicken Sie auf den **Konfiguren** Link des **Zahlungsmittels** welches Sie aktivieren möchten.

4. Füllen Sie hier die **Site Id** und den **Hash Key** ein, welche Sie unter **Webseite** bei [**Mein CardGate**](https://my.cardgate.com/) finden können.

5. Wählen Sie die **Währung** aus, die Sie verwenden möchten.

6. Füllen Sie Standard **Gateway Sprache** ein.

7. Falls Sie von Logoption Gebrauch machen wollen, kontrollieren Sie dan ob der Log-Ordner Ihrer Website schreib rechten haben.    
   z.B. Der Ordner **http://mywebshop.com/payment/cardgateplus/logs**.  

8. Klicken Sie auf den Button **Update** und speichern Sie die Einstellungen.

9. Klicken Sie erneut auf **Einstellungen** und klicken Sie auf **Zahlungsmittel**.

10. Wählen Sie das Zahlungsmittel aus, dass Sie eingestellt haben und verändern Sie, falls gewünscht den Namen des Zahlungsmittel.    
    Klicken Sie nun auf **Apply Changes**.

11. Wiederholen Sie die Schritte **3 bis 10** für **jedes Zahlungsmittel**, dass Sie installieren möchten.

12. Gehen Sie zu [**Mein CardGate**](https://my.cardgate.com/), klicken Sie auf **Webseite** und wählen Sie der richtige Webseite aus.  

13. Füllen Sie bei Schnittstelle die **Callback URL** ein:  
    Die **Callback URL** wird in jeder Zahlungsmethode angezeigt und kann direkt kopiert werden.

14. Falls Sie für mehrere Zahlungsmethoden die **selbe** Site ID und **den selben** Hash Key verwenden,   
    können Sie die Callback URL einer **beliebigen CardGate Zahlungsmethode** verwenden,  
    solang diese **aktiv** ist.  
    Dieses Callback kann auch die Callbacks anderer CardGate Zahlungsmethoden verarbeiten.

15. Entfernen Sie aus Sicherheitsgründen den **install_cardgateplus** Ordner von Ihrem Webshop.

16. Wenn Sie mit dem  **Testen abgeschlossen** haben, schalten Sie **alle aktivierten Zahlungsmethoden** von dem  
    **Testmodus** in den **Livemodus** und klicken Sie auf (**Speichern**).

## Anforderungen

Keine weiteren Anforderungen.
