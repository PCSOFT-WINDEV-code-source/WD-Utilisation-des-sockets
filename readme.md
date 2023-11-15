  
<span style="font-family:Arial sans-serif;font-size:16px;">WD Utilisation des sockets</span>

  
<span style="font-family:Arial sans-serif;font-size:14px;">Cet exemple illustre les fonctions "Socket" de WINDEV dans une utilisation de type client/serveur.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">Dans cet exemple, nous abordons deux thèmes principaux :</span>

<span style="font-family:Arial sans-serif;font-size:14px;">1/ Comment se connecter à une socket</span>

<span style="font-family:Arial sans-serif;font-size:14px;">2/ Comment accepter une demande de connexion</span>

<span style="font-family:Arial sans-serif;font-size:14px;">3/ Comment écrire ou lire sur une socket</span>

<span style="font-family:Arial sans-serif;font-size:14px;">Résumé de l'exemple livré avec WINDEV : </span>

<span style="font-family:Arial sans-serif;font-size:14px;">Cet exemple présente les différentes fonctions de gestion des sockets livrées en standard avec WINDEV. Pour utiliser cet exemple, il est nécessaire de lancer une première instance de l'exemple en mode "serveur". Ensuite, en donnant le nom de la machine faisant office de serveur et un pseudonyme, vous pouvez vous connecter à cette application en mode "client". Il est alors possible d'envoyer des messages à tous les utilisateurs connectés. Dans cet exemple, à chaque connexion est associée : un thread et une socket . </span>

  
  
<span style="font-family:Arial sans-serif;font-size:14px;">( \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ° \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ )</span>

  
<span style="font-family:Arial sans-serif;font-size:10px;">Conditions d'utilisation :</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Le programme est fourni dans un but didactique.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">L'utilisation de ce programme s'effectue sous la responsabilité de son utilisateur. La responsabilité de PC SOFT ne pourra en aucun cas être mise en cause si le programme ne fonctionne pas tel que vous l'attendez, ou pour quelque raison que ce soit. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">Tout détenteur d'une licence WINDEV 28 enregistrée est autorisé à modifier ce programme, et est autorisé à l'inclure dans une ou plusieurs de ses applications. Dans ces cas, toute mention se rapportant à PC SOFT, à WinDev ou à WebDev devra être supprimée, afin qu'aucun doute ne puisse subsister dans l'esprit d'un utilisateur final.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Il est interdit de diffuser ou vendre ce programme exemple sans modification substantielle, ou sans l'inclure dans une application de taille substantielle.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Le support technique pour ce programme exemple est accessible à travers le service "Assistance Directe" uniquement.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Attention: si plusieurs personnes sont susceptibles d'avoir consulté ce programme, il se peut que le programme ait été modifié! </span>

<span style="font-family:Arial sans-serif;font-size:10px;">Assurez-vous d'étudier une version originale de ce programme.</span>

  
  