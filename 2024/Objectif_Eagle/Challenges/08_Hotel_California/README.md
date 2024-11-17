# 08 - HOTEL CALIFORNIA

### ENONCE :

> **Yves Ferrandi** s'est souvenu d'une anecdote qui n'a inquiété personne à l'époque. **Marco Verecchio s'était fait voler son laptop** durant le **salon Eurosatory 2022**. Aucune plainte n'avait été déposée et le directeur technique n'avait même pas fait de rapport d'incident.

> Si ce n'est pas sur le stand, dans quel hotel a t-il pu être volé ? 

### FORMAT DU FLAG : `ibiza_motel_lyon`

## INVESTIGATION :

1. Sur le profil Facebook de **Marco Verecchio**, nous pouvons voir sur la page "[A Propos](https://www.facebook.com/profile.php?id=61566958176024&sk=about_contact_and_basic_info)" que son adresse e-mail est `marco.verecchio@gmail.com`.

2. Une recherche sur [EPIOS](https://epieos.com/?q=marco.verecchio%40gmail.com&t=email) nous donne un lien vers son calendrier Google partagé.
    - https://calendar.google.com/calendar/u/0/embed?src=marco.verecchio@gmail.com

3. Nous pouvons voir que le **dimanche 12 juin 2022**, il y a l'évenement suivant :
    > **Arrivée Eurosatory 2022**
    > 
    > *Dimanche, 12 juin 2022·16:30 à 17:30*
    > 
    > Pour demain matin **350m + B**. Prévoir **16mn**.
    > 
    > Laisser l'ordi à l'hôtel.

5. Nous devons trouver l'hôtel où Marco à séjourné.
    - Une longue recherche sur **Google Maps** nous donne l'**[Egg Hôtel Servan](https://maps.app.goo.gl/wsCaXaq3fiicE91v6)**.

### FLAG VALIDE : `egg_hotel_sevran`
