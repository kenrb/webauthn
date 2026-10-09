# [Self-Review Questionnaire: Security and Privacy](https://w3c.github.io/security-questionnaire/)

This is the self-review questionnaire for the Web Authentication [Conditional UI without Autofill feature proposal](https://github.com/w3c/webauthn/blob/main/explainers/conditional-ui-without-autofill.md).

---

01.  What information does this feature expose, and for what purposes?

There is no change that affects what information is available to websites compared to the current Conditional UI WebAuthn feature. This only changes the UI that is shown to the user.

02.  Do features in your specification expose the minimum amount of information necessary to implement the intended functionality?

Yes.

03.  Do the features in your specification expose personal information, personally-identifiable information (PII), or information derived from either?

The authentication assertion contains PII. There is no change from existing behaviour of the specification in that regard.

04.  How do the features in your specification deal with sensitive information?

See the [Privacy Assertions section of the specification](https://www.w3.org/TR/webauthn-3/#sctn-privacy-considerations). There are no changes associated with this feature.

05.  Does data exposed by your specification carry related but distinct information that may not be obvious to users?

See the [Privacy Assertions section of the specification](https://www.w3.org/TR/webauthn-3/#sctn-privacy-considerations). There are no changes associated with this feature.

06.  Do the features in your specification introduce state that persists across browsing sessions?

See the [Privacy Assertions section of the specification](https://www.w3.org/TR/webauthn-3/#sctn-privacy-considerations). There are no changes associated with this feature.

07.  Do the features in your specification expose information about the underlying platform to origins?

See the [Privacy Assertions section of the specification](https://www.w3.org/TR/webauthn-3/#sctn-privacy-considerations). There are no changes associated with this feature.

08.  Does this specification allow an origin to send data to the underlying platform?

Yes. See the [Privacy Assertions section of the specification](https://www.w3.org/TR/webauthn-3/#sctn-privacy-considerations). There are no changes associated with this feature.

09.  Do features in this specification enable access to device sensors?

No.

10.  Do features in this specification enable new script execution/loading mechanisms?

No.

11.  Do features in this specification allow an origin to access other devices?

Yes. See the [Privacy Assertions section of the specification](https://www.w3.org/TR/webauthn-3/#sctn-privacy-considerations). There are no changes associated with this feature.

12.  Do features in this specification allow an origin some measure of control over a user agent's native UI?

Yes. The proposed change allows the website to request UI that is currently shown as part of autofill to appear as a browser dialog or bubble.

13.  What temporary identifiers do the features in this specification create or expose to the web?

None.

14.  How does this specification distinguish between behavior in first-party and third-party contexts?

WebAuthn get invocations from a third-party context require a permissions policy. This feature does not change that.

15.  How do the features in this specification work in the context of a browser’s Private Browsing or Incognito mode?

There is no change of behaviour.

16.  Does this specification have both "Security Considerations" and "Privacy Considerations" sections?

The Web Authentication specification does. This feature does not require changes to them.

17.  Do features in your specification enable origins to downgrade default security protections?

No.

18.  What happens when a document that uses your feature is kept alive in BFCache (instead of getting destroyed) after navigation, and potentially gets reused on future navigations back to the document?

No change to existing WebAuthn behaviour.

19.  What happens when a document that uses your feature gets disconnected?

No change to existing WebAuthn behaviour.

20.  Does your spec define when and how new kinds of errors should be raised?

No.

21.  Does your feature allow sites to learn about the user's use of assistive technology?

No.

22.  What should this questionnaire have asked?

¯\\\_(ツ)\_/¯
