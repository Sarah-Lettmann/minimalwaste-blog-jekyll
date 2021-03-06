---
uid: "0025"
title: "Plastikfrei einkaufen: Alle Onlineshops"
subtitle: "Wo du plastik- und müllfreie Produkte online findest"
date: 2017-09-17
categories: [Zero Waste]
description: "Plastikfrei einkaufen und zwar online. Ja, auch das geht! Auf dieser Seite findest du eine Liste mit Onlineshops bei denen du plastikfrei einkaufen kannst."
keywords: [plastikfrei einkaufen]
related-posts: ["0064", "0073", "0037", "0013", "0014", "0065"]
---
Plastikfrei einkaufen und zwar online. Ja, auch das geht! Auf dieser Seite findest du eine Liste mit Onlineshops, die sich plastikfreies Einkaufen auf die Fahne geschrieben haben. Natürlich kommen auch diese in einem Paket, aber die verkauften Artikel sind nachhaltig produziert, unterstützen dich beim Müllvermeiden oder sind eben plastikfrei. Ebenso wird in den meisten Fällen kein Plastik für die Polsterung oder Verpackung verwendet.

Nachhaltiger online shoppen ist also möglich. Du solltest aber immer im Hinterkopf haben, dass auch weniger Konsum einen großen Teil zu einem nachhaltigeren Lebensstil beiträgt. Falls du aber keine passenden Alternativen bei dir in der Nähe hast, sind diese Shops ideal. Viel Spaß beim Stöbern!
<!--more-->

<mark>Kennst du Onlineshops die ohne Plastikverpackung oder Polsterung versenden? Oder die vielleicht einfach nur nachhaltig produzierte Produkte verkaufen?</mark> Schreib mir einfach eine Mail an [info@minimalwaste.de](mailto:info@minimalwaste.de) und ich werde sie in die Liste mit aufnehmen.

<table>
  <thead>
    <tr>
      <th>URL</th>
      <th>Produkte</th>
      <th>Sitz in</th>
    </tr>
  </thead>
  <tbody>
    {% for shop in site.data.onlineshops-plastikfrei %}
      <tr>
        <td data-label="URL"><a href="{{ shop.url }}">{{ shop.name }}</a></td>
        <td data-label="Produkte">{{ shop.products }}</td>
        <td data-label="Sitz in">{{ shop.located }}</td>
      </tr>
    {% endfor %}
  </tbody>
</table>

Wie immer würde ich mich über Feedback und Ergänzungen freuen. Bis zum nächsten Mal.

\- Sarah
