# Conclusion

In our guide, we examined the features of popular mobile frameworks in terms of architecture. By themselves, cross-platform applications are very fast and comparable to native ones, but the need to use the bridge slightly reduces the speed when interacting with native APIs.

**General conclusion: all popular cross-platform frameworks use a bridge that reduces the speed of interaction with the native part. Bottlenecks \(specific for each framework\) should be optimized when creating the user interface. The final choice of the framework will depend on the competencies available in the team and the requirements of the final result.**

When choosing a framework, it is necessary to take into account not only the programming language, but also the required level of knowledge of the target operating systems \(iOS, Android, Windows\), and also draw on the experience of your development team. For example, when you use PhoneGap, you can get by with superficial OS knowledge if you do not need to manually implement the platform functionality. And for Xamarin Classic, one will have to become an expert in iOS and/or Android.

As a result, let's collect all the recommendations for choosing the frameworks in one place:

* **PhoneGap** - if you need to quickly make a simple application or prototype and the team has experience developing single-page web applications \(HTML, JavaScript, CSS\). In most cases, you can do with ready-made plug-ins for native functionality. Of the minuses - non-native interface with frequent freezings and difficult access to the native part. The percentage of shared code is up to 95%.
* **ReactNative** - perfect for experienced JavaScript developers and commands, but will require a good knowledge of the iOS Objective C API and Android Java API. Applications look and work natively, but also consider the young stage of the framework. The percentage of shared code is up to 90%.
* **Xamarin Classic** - if you have experienced C\# developers, they will need to master iOS and Android deeply. Applications will be completely native, although written in C\#. The shared code base in rare cases exceeds 40%.
* **Xamarin.Forms** - suitable for experienced C\# -developers, especially with knowledge of XAML. For applications with a simple interface \(standard controls\), you do not need deep knowledge of iOS/Android/Windows. The percentage of shared code is up to 90%.
* **Qt** - this framework can be recommended only if you already have an existing application \(for example, embedded\) and it needs to be run on iOS/Android. High requirements for developers' skills, uneasy access to native functionality and non-native UI are notable shortcomings of the framework. The percentage of shared code can reach up to 95%.

Slava Chernikoff, slava@binwell.com

Our contact info: [binwell.com](https://binwell.com), +7 \(499\) 677-49-27, contact@binwell.com.

You can also subscribe to our Medium, where we often post interesting materials on cross-platform mobile applications development on Xamarin and Xamarin.Forms, and material on architecture and development technologies, as well as Mobile DevOps: [medium.com/binwell](https://medium.com/binwell)

![](.gitbook/assets/fb-logo.jpg)

