---
layout: post
title:  "Witaj Świecie!"
date:   2020-11-25 23:23:23 +0100
categories: [programowanie, java]
description: Blog powstal w celu zamieszczania informacji ze świata programowania i rozwoju osobistego.
tags: [programowanie, java]
---
Na dobry początek warto się przywitać😉

Zróbmy to za pomocą prostej, publicznie dostępnej (w danym projekcie), nie zwracającej żadnego typu (void), statycznej (bez konieczności tworzenia obiektu) funkcji witającej:
{% highlight java %}
  public static void hello(String name) {
    System.out.println("Witaj " + name);
  }

  hello("Mistrzu");

  //Rezultat: 'Witaj Mistrzu' w konsoli.
{% endhighlight %}