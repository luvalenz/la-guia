Rails
=====

* Inicializamos nuestros proyectos con [potassium](https://github.com/platanus/potassium)
* El deploy se hace con [negroku](https://github.com/platanus/negroku)
* Cuando nuestros proyectos incluyen una API Rails, utilizamos la gema [simple_token_authentication](https://github.com/gonzalo-bulnes/simple_token_authentication) para manejar la autenticación. Más información en este [blog post](http://cb.platan.us/rails/authentication/restmod/angular/2015/03/13/usando-angular-auth-lib-con-simple-token-authentication-gem.html)
* Las interfaces de administración las contruimos usando [Active Admin](/code/activeadmin.md)
* Para resolver el problema de autenticar usuarios que no pueden registrarse libremente en una aplicación utilizamos [devise_invitable](http://cb.platan.us/rails/active%20admin/devise/2015/03/18/invitar-usuarios-con-devise.html)
* Para manejar "Enum attributes" utilizamos la gema [enumerize](https://github.com/brainspec/enumerize)
* Como estrategia para el manejo de attachments en nuestras APIs, usamos la gema [paperclip_upload](https://github.com/platanus/paperclip_upload)

{% getPostsByTag 'rails', 'ruby' %}{% endgetPostsByTag %}