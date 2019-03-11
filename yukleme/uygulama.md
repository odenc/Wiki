---
description: >-
  Bu sayfa ile PreMiD uygulamasını bilgisayarınıza nasıl yükleyeceğinizi
  öğrenebilirsiniz.
---

# Uygulama

{% hint style="warning" %}
  
PreMiD'in çalışması için eklentiyi ve programı yüklemeniz gerekmektedir!
{% endhint %}

Uygulamayı yüklemek, eklenti kendi başına hiçbir iş yapamayacağından dolayı çok önemlidir. Bu yüzden aşağıdan işletim sisteminizi seçerek yükleme işlemlerini takip edin.

{% tabs %}
{% tab title="Windows" %}
[Buraya](https://premid.app/downloads) tıklayarak işletim sisteminiz için uygun olan sürümü indirin.

![&#x130;ndirme sayfas&#x131;](https://camo.githubusercontent.com/db35e8b9473dadc5e2712cf74c2e3f4a11be0bcc/68747470733a2f2f626c6f627363646e2e676974626f6f6b2e636f6d2f76302f622f676974626f6f6b2d32383432372e61707073706f742e636f6d2f6f2f6173736574732532462d4c4e4c736b56596d346a5670684d44597474502532462d4c576c64585868695f654e66454e67304a43612532462d4c576c64636e324b43526f6e6e4a784c4f6442253246766976616c64695f323031392d30312d32315f32312d32312d35322e706e673f616c743d6d6564696126746f6b656e3d38326134393435622d336431632d346366642d626239362d373732346262386432313331)

İndirme bittiğinde indirdiğiniz dosyayı açın. Dosya açıldığında Windows SmartScreen, size bunun gibi bir uyarı verecektir. Bu, programın henüz Microsoft tarafından tanınmamasından dolayıdır. Söz veriyoruz, bu uygulamada herhangi bir virüs yoktur! İsterseniz kaynak kodlarını GitHub'dan görebilirsiniz.

![SmartScreen uyar&#x131;s&#x131;](https://camo.githubusercontent.com/686b1d78d5232ed8a13cfd484ef59bccc83a2e02/68747470733a2f2f626c6f627363646e2e676974626f6f6b2e636f6d2f76302f622f676974626f6f6b2d32383432372e61707073706f742e636f6d2f6f2f6173736574732532462d4c4e4c736b56596d346a5670684d44597474502532462d4c576c4d6b586f626b504b34517344414733622532462d4c576c576d5179764f6e523138704246564e71253246323031392d30312d32315f32302d34382d31342e706e673f616c743d6d6564696126746f6b656e3d34313331353933322d383733392d346539662d393835642d663364633066383836386361)

Uygulama otomatik olarak yüklenecek ve yükleme bittikten sonra kendini başlatacaktır. Uygulamanın başlayıp başlamadığını anlamak için görev çubuğunuza bakabilirsiniz.

![G&#xF6;rev &#xC7;ubu&#x11F;u simgesi](https://camo.githubusercontent.com/abe646c205b9fef9f6dd07409d2bccc2fe985828/68747470733a2f2f7468652d706572736f6e2d756e6465722d746869732d6d6573736167652e69732d696e736964652e6d652f4e68486a353349642e706e67)

Sonunda, eğer her şeyi düzgün yüklediyseniz, [desteklenen servislerden](../destek/servisler.md) birini ziyaret edebilir ve PreMiD'in zevkini sürebilirsiniz.
{% endtab %}

{% tab title="Mac OS" %}
1. [Uygulamanın](https://github.com/Timeraa/YT-Presence/releases/latest) son sürümünü indirin.
2. İndirilen `.dmg` dosyasını açın.
3. **PreMiD**'i **Uygulamalar** dosyanıza taşıyın.
4. Launchpad'inizi açın veya F4'e basın.
5. **PreMiD**'i açın.
6. Eğer bir izin penceresi açılırsa "**İzin Ver**"e basın.
7. Eğer hala [eklentiyi](eklenti.md) yüklemediyseniz, yükleyin.
{% endtab %}

{% tab title="Linux" %}
{% hint style="info" %}
Eğer GNU/Linux desteği istiyorsanız, aşağıdaki [bu](https://github.com/Timeraa/PreMiD/issues/21) bildiriyi destekleyin.
{% endhint %}

1. GitHub deposunu klonlayın: `git clone https://github.com/Timeraa/PreMiD.git`
2. Kaynağın içine girin: `cd PreMiD/src`
3. "npm"yi kullanarak yüklemeyi başlatın: `npm install`
4. Uygulamayı başlatın: `npm start`
{% endtab %}
{% endtabs %}

