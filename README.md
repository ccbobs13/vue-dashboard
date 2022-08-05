# PROJET VUE.JS  • vue-dashboard

## DAGA Eunicia Neruda
## THIOMBIANO Samyr Christian Yentéma

## Lien de l'application [cliquez-ici](https://ccbobs13.github.io/vue-dashboard/)
***

# API Info

<p> Notre API est une API REST de paiment VueJs.
Elle a des URL prévisibles orientées ressources.
L'API prend en charge les requetes sous format JSON uniquement.
</p>
<h3>Endpoints Disponibles</h3>
<ul>
  <li>
    /api/auth: Endpoint de base pour toutes les requetes
    concernant l'authentification.
  </li>
  <li>
    /api/user: Endpoint de base pour toutes les requetes
    concernant l'utilisateur.
  </li>
  <li>
    /api/payment: Endpoint de base pour toutes les requetes
    concernant le paiement.
  </li>
</ul>
<h3>Formats Supportés</h3>
<p>
  L'API prend en charge les requetes sous format JSON uniquement
</p>

## 
# Documentation de l'API

<h3>Endpoints</h3>
<h5>• Authentification (/api/auth/)</h5>
<p class="body-1">
  Method: post <br />
  Route: "/auth/signup" <br />
  Usage: Enregistrer un nouvel utilisateur <br />
  Body: {email, password, password_confirm}<br />
  <img width="454" alt="image" src="https://user-images.githubusercontent.com/96637804/183141783-1a078aff-20cf-441b-8894-db4ce1c54982.png">

  Method: post <br />
  Route: "/auth/signin" <br />
  Usage: Se connecter <br />
  Body: {email, password, password_confirm}<br />
  <img width="454" alt="image" src="https://user-images.githubusercontent.com/96637804/183141681-9932c12e-9dbd-4872-81a8-65e9888739b2.png">

  Method: post <br />
  Route: "/auth/signout" <br />
  Usage: Se déconnecter <br />
  Body: {}<br />

  Method: post <br />
  Route:"/auth/password-reset" <br />
  Usage: Reinitialiser son mot de passe <br />
  Body: {email}<br /><br />
  <img width="454" alt="image" src="https://user-images.githubusercontent.com/96637804/183141898-e2426436-6287-4389-8570-b580725bb058.png">
</p>

<h5>• Paiement (/api/payment/)</h5>
<p class="body-1">
  Method: post<br />
  Route("/payment" ) <br />
  Usage: Effectuer un paiement <br />
  Body: {articles, testUserEmail, options}<br /><br />
</p>

<h5>• Utilisateur (/api/user/)</h5>
<p class="body-1">
  Method: put <br />
  Route: "/user/update" <br />
  Usage: Modifier un utilisateur <br />
  Body: {Utilisateur}<br />
</p>
<p class="body-1">
  Method: post <br />
  Route:"/user/password/update" <br />
  Usage: Mettre a jour son mot de passe <br />
  Body: {token, password}<br />
  <img width="454" alt="image" src="https://user-images.githubusercontent.com/96637804/183141981-4aa6e793-d876-4ad7-b8f9-18d50551ee0e.png">

</p>
<p class="body-1">
  Method: get <br />
  Route: "/user/profile" <br />
  Usage: Afficher le profile d'un utilisateur <br />
  Body: {}<br />
  <img width="454" alt="image" src="https://user-images.githubusercontent.com/96637804/183142025-6d0d1ff5-4914-4ec9-9437-a3989212d0c7.png">

</p>
<p class="body-1">
  Method: put <br />
  Route: "/user/profile/update" <br />
  Usage: Modifier le profile d'un utilisateur <br />
  Body: {Profile}<br />
  <img width="454" alt="image" src="https://user-images.githubusercontent.com/96637804/183142062-ef24251f-d9dc-47e0-9ded-a7a145ebd6fe.png">

</p>
<p class="body-1">
  Method: get <br />
  Route: "/user/account" <br />
  Usage:Afficher le compte d'un utilisateur <br />
  Body: {}<br />
  <img width="454" alt="image" src="https://user-images.githubusercontent.com/96637804/183142092-35b71865-4297-4bdb-8d49-6e1f1abae337.png">

</p>
<p class="body-1">
  Method: get <br />
  Route: "/user/account/mail/:email" <br />
  Usage: Récupérer l'utilisateur de test grace à son mail <br />
  Params: {email}<br />
</p>
<p class="body-1">
  Method: put <br />
  Route: "/user/account/update" <br />
  Usage: Modifier le compte de l'utilisateur test <br />
  Body: {Account}<br />
</p>
<p class="body-1">
  Method: get <br />
  Route: "/user/transaction"<br />
  Usage: Renvoie toutes les transactions que l'utilisateur a
  effectué <br />
  Body: {}<br />
  <img width="454" alt="image" src="https://user-images.githubusercontent.com/96637804/183142124-c84ec8b6-ab1c-4a5a-89a6-ecc7705ac9b8.png">

</p>
<p class="body-1">
  Method: get <br />
  Route: "/user/transaction/:email"<br />
  Usage: Renvoie toutes les transactions que l'utilisateur a
  effectué grace a so email <br />
  Params: {email}<br />
  <img width="454" alt="image" src="https://user-images.githubusercontent.com/96637804/183142153-79f7c040-1fc3-492f-8e88-39c8d5713b47.png">

</p>
