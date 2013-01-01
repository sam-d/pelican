Pelican
#######

Pelican est un generateur de blog simple codé en python

* Écrivez vos articles directement dans votre éditeur favori (vim !) et
  directement en syntaxe reStructuredText ou Markdown ;
* Un outil simple en ligne de conmmande pour (re)générer le blog ;
* Sortie complètement statique, facile pour l'héberger n'importe où ;

Fonctionnalités
===============

Pelican supporte actuellement :

* des articles de blog ;
* des pages statiques ;
* les commentaires via un service externe (`disqus <http://disqus.com>`_)
  Notez qu'étant bien un service externe assez pratique, vous ne gérez pas
  vous même les commentaires. Ce qui pourrait occasionner une perte de vos données;
* support de template (les templates sont crées avec `jinja2 <http://jinjna.pocoo.org>`_) ;
* génération optionnelle de vos pages et articles en pdf.

Pourquoi le nom "Pelican" ?
============================

Vous n'avez pas remarqué ? "Pelican" est un anagramme pour "Calepin"  ;)

Code source
===========

Vous pouvez accéder au code source via git à l'adresse 
http://github.com/getpelican/pelican/

Feedback !
==========

Si vous voulez de nouvelles fonctionnalitées pour Pelican, n'hésitez pas à nous le dire,
à cloner le dépôt, etc … C'est open source !!!

Contactez Alexis à "alexis at notmyidea dot org" pour quelques requêtes ou retour d'expérience que ce soi !

Documentation
=============

.. toctree::
   :maxdepth: 2
   
   conventions
   installation
   bases
   configuration
   themes
   parametres_article
   astuces
   faq
   pelican-themes
