---
description: "Verfügbare Microsoft-Lösung zum Schützen zusätzlicher Produkte"
layout: ContentPage
hide_bc: True
redirect_url: https://blogs.technet.microsoft.com/msrc/2017/05/12/customer-guidance-for-wannacrypt-attacks/
ms.openlocfilehash: b860cc57010e2d311215c74deaca54e2f4ca3a45
ms.sourcegitcommit: 6634eef2e124f7e6ce7e25fa8a9e9655d94fae27
ms.translationtype: HT
ms.contentlocale: de-AT
ms.lasthandoff: 06/01/2017
---
# <a name="customer-guidance-for-wannacrypt-attacks"></a>Kundenleitfaden für WannaCrypt-Angriffe

12. Mai 2017

## <a name="microsoft-solution-available-to-protect-additional-products"></a>Verfügbare Microsoft-Lösung zum Schützen zusätzlicher Produkte

Heute waren weltweit viele unserer Kunden und die kritischen Systeme, auf die sie sich verlassen, Opfer der Schadsoftware „WannaCrypt“. Zu erleben, wie Unternehmen und Personen von Cyberangriffen wie diesem betroffen waren, der heute gemeldet wurde, war schmerzlich. Bei Microsoft wurde den ganzen Tag durchgearbeitet, um herauszufinden, worum es sich bei dem Angriff handelte, und es wurden alle denkbaren Maßnahmen ergriffen, um unsere Kunden zu schützen. In diesem Blog werden die Schritte beschrieben, die Einzelpersonen und Unternehmen ausführen müssen, um geschützt zu bleiben. Darüber hinaus haben wir uns zu dem überaus ungewöhnlichen Schritt entschlossen, ein Sicherheitsupdate für alle Windows-Plattformen bereitzustellen, die benutzerdefiniertem Support unterliegen, einschließlich Windows XP, Windows 8 und Windows Server 2003. Kunden mit Windows 10 waren von dem heutigen Angriff nicht betroffen.

Es folgen die Details.

* Im März haben wir ein Sicherheitsupdate veröffentlicht, das die Sicherheitslücke schließt, die von diesen Angriffen ausgenutzt wird. Benutzer mit aktiviertem Windows Update sind gegen Angriffe auf diese Schwachstelle geschützt. Organisationen, die das Sicherheitsupdate noch nicht angewendet haben, empfehlen wir das sofortige Einspielen des [Microsoft-Sicherheitsbulletins MS17-010](https://technet.microsoft.com/en-us/library/security/ms17-010.aspx).
* Für Kunden mit Windows Defender haben wir früher am heutigen Tag ein Update veröffentlicht, das diese Bedrohung als [Ransom:Win32/WannaCrypt](https://www.microsoft.com/security/portal/threat/encyclopedia/Entry.aspx?Name=Ransom:Win32/WannaCrypt) erkennt. Als zusätzliche tiefgreifende Vorbeugungsmaßnahme sollten Sie die auf Ihren Computern installierte Antischadsoftware auf dem neuesten Stand halten. Kunden mit Antischadsoftware verschiedener anderer Anbieter können diese befragen, ob sie geschützt sind.
* Dieser Angriffstyp kann sich mit der Zeit weiterentwickeln, weshalb zusätzliche tiefgreifende Abwehrstrategien für zusätzlichen Schutz sorgen werden. (Als zusätzlichen Schutz gegen [SMBv1-Angriffe](https://aka.ms/disablesmb1) sollten Kunden beispielsweise das Blockieren älterer Protokolle in ihren Netzwerken erwägen.)

Wir wissen auch, dass einige unserer Kunden Versionen von Windows ausführen, die keinen Mainstream-Support mehr erhalten. Dies bedeutet, dass diese Kunden nicht das zuvor erwähnte im März veröffentlichte Sicherheitsupdate erhalten haben. Angesichts der möglichen Auswirkungen auf Kunden und ihre Unternehmen haben wir die Entscheidung getroffen, das Sicherheitsupdate umfassend für Plattformen, für die es nur noch benutzerdefinierten Support gibt, nämlich Windows XP, Windows 8 und Windows Server 2003 (siehe die nachstehenden Links) zum Download zur Verfügung zu stellen.

Kunden mit unterstützten Betriebssystemversionen (Windows Vista, Windows Server 2008, Windows 7, Windows Server 2008 R2, Windows 8.1, Windows Server 2012, Windows 10, Windows Server 2012 R2, Windows Server 2016) haben das Sicherheitsupdate MS17-010 im März erhalten. Kunden, die automatische Updates aktiviert haben oder das Update installiert haben, sind geschützt. Anderen Kunden raten wir, das Update so bald wie möglich zu installieren.

Diese Entscheidung erfolgte auf Grundlage einer Bewertung dieser Situation unter eingehender Berücksichtigung des Prinzips des allgemeinen Schutzes des Ökosystems unserer Kunden.

Bei einigen der beobachteten Angriffe kommen gängige Phishing-Methoden zum Einsatz, einschließlich mit Schadsoftware verseuchter Anlagen. Kunden sollten unbedingt wachsam sein, wenn sie Dokumente aus nicht vertrauenswürdigen oder unbekannten Quellen öffnen. Für Office 365-Kunden erfolgt eine laufende Überwachung und Aktualisierung zum Schutz vor diese Arten von Bedrohungen, einschließlich Ransom:Win32/WannaCrypt. Weitere Informationen zur Schadsoftware selbst finden Sie im Blog „Windows Security: The new Microsoft Malware Protection Center“. Das neue Microsoft Malware Protection Center bietet eine technische Diskussion mit dem Schwerpunkt, IT-Sicherheitsexperten mit Informationen zum zusätzlichen Schutz von Systemen zu versorgen.

Wir arbeiten mit Kunden zusammen, um abhängig davon, wie sich diese Situation entwickelt, weitere Unterstützung zu bieten. Außerdem aktualisieren wir diesen Blog mit entsprechenden Details.

Phillip Misner, Principal Security Group Manager, Microsoft Security Response Center

## <a name="further-resources"></a>Weitere Ressourcen:

<p>Herunterladen englischsprachiger Sicherheitsupdates: <a href="http://download.windowsupdate.com/d/csa/csa/secu/2017/02/windowsserver2003-kb4012598-x64-custom-enu_f24d8723f246145524b9030e4752c96430981211.exe">Windows Server 2003 SP2 x64</a>, <a href="http://download.windowsupdate.com/c/csa/csa/secu/2017/02/windowsserver2003-kb4012598-x86-custom-enu_f617caf6e7ee6f43abe4b386cb1d26b3318693cf.exe">Windows Server 2003 SP2 x86,</a> <a href="http://download.windowsupdate.com/d/csa/csa/secu/2017/02/windowsserver2003-kb4012598-x64-custom-enu_f24d8723f246145524b9030e4752c96430981211.exe">Windows XP SP2 x64</a>, <a href="http://download.windowsupdate.com/d/csa/csa/secu/2017/02/windowsxp-kb4012598-x86-custom-enu_eceb7d5023bbb23c0dc633e46b9c2f14fa6ee9dd.exe">Windows XP SP3 x86</a>, <a href="http://download.windowsupdate.com/c/csa/csa/secu/2017/02/windowsxp-kb4012598-x86-embedded-custom-enu_8f2c266f83a7e1b100ddb9acd4a6a3ab5ecd4059.exe">Windows XP Embedded SP3 x86</a>, <a href="http://download.windowsupdate.com/c/msdownload/update/software/secu/2017/05/windows8-rt-kb4012598-x86_a0f1c953a24dd042acc540c59b339f55fb18f594.msu">Windows 8 x86,</a> <a href="http://download.windowsupdate.com/c/msdownload/update/software/secu/2017/05/windows8-rt-kb4012598-x64_f05841d2e94197c2dca4457f1b895e8f632b7f8e.msu">Windows 8 x64</a></p>
<p>Herunterladen lokalisierter Sicherheitsupdates: <a href="http://www.microsoft.com/downloads/details.aspx?FamilyId=d3cb7407-3339-452e-8371-79b9c301132e">Windows Server 2003 SP2 x64</a>, <a href="http://www.microsoft.com/downloads/details.aspx?FamilyId=350ec04d-a0ba-4a50-9be3-f900dafeddf9">Windows Server 2003 SP2 x86,</a><a href="http://www.microsoft.com/downloads/details.aspx?FamilyId=5fbaa61b-15ce-49c7-9361-cb5494f9d6aa">Windows XP SP2 x64</a>, <a href="http://www.microsoft.com/downloads/details.aspx?FamilyId=7388c05d-9de6-4c6a-8b21-219df407754f">Windows XP SP3 x86</a>, <a href="http://www.microsoft.com/downloads/details.aspx?FamilyId=a1db143d-6ad2-4e7e-9e90-2a73316e1add">Windows XP Embedded SP3 x86</a>, <a href="http://www.microsoft.com/downloads/details.aspx?FamilyId=6e2de6b7-9e43-4b42-aca2-267f24210340">Windows 8 x86,</a><a href="http://www.microsoft.com/downloads/details.aspx?FamilyId=b08bb3f1-f156-4e61-8a68-077963bae8c0">Windows 8 x64</a></p>
<p>Allgemeine Informationen zu Ransomware: <a href="https://www.microsoft.com/en-us/security/portal/mmpc/shared/ransomware.aspx">https://www.microsoft.com/en-us/security/portal/mmpc/shared/ransomware.aspx</a></p>
<p>Sicherheitsupdate MS17-010: <a href="https://technet.microsoft.com/en-us/library/security/ms17-010.aspx">https://technet.microsoft.com/de-at/library/security/ms17-010.aspx</a></p>
