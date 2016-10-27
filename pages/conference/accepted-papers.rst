.. title: Accepted Papers
.. slug: accepted-papers
.. date: 2016-10-27 14:09:08 UTC+13:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

.. contents::

.. raw:: html

   <style>
     div.paper-abstract {
       margin: 10px 10px 10px 10px;
       display: none;
     }
     span.paper-abstract-link {
       color: #be0403;
     }
     span.paper-abstract-link:hover {
       text-decoration: underline;
     }
   </style>

   <script>
     function toggleAbstracts() {
       $(".paper-title").click( function() {    
           $(this).children(".paper-abstract").toggle();
       });
       var hash = window.location.hash;
       if (hash != "")
         $(hash).parent().click();
     }
     window.onload = toggleAbstracts;
   </script>


Conference Track
================

.. include:: pages/conference/accepted-papers_conference.rst


Journal Track
=============

.. include:: pages/conference/accepted-papers_journal.rst

