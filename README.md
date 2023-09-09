## PayPal Checkout

[![build status][build-badge]][build]
[![code coverage][coverage-badge]][coverage]
[![npm version][version-badge]][package]
[![apache license][license-badge]][license]

[build-badge]: https://img.shields.io/github/workflow/status/paypal/paypal-checkout-components/build?logo=github&style=flat-square
[build]: https://github.com/paypal/paypal-checkout-components/actions?query=workflow%3Abuild
[coverage-badge]: https://img.shields.io/codecov/c/github/paypal/paypal-checkout-components.svg?style=flat-square
[coverage]: https://codecov.io/github/paypal/paypal-checkout-components/
[version-badge]: https://img.shields.io/npm/v/@paypal/checkout-components.svg?style=flat-square
[package]: https://www.npmjs.com/package/@paypal/checkout-components
[license-badge]: https://img.shields.io/npm/l/@paypal/checkout-components.svg?style=flat-square
[license]: https://github.com/paypal/paypal-checkout-components/blob/main/LICENSE


**Fundamental Application**

The subsequent gateways are extended through the utilization of this package:

- PayPal_Express (Facilitator of PayPal's Express Checkout)
- PayPal_ExpressInContext (Embedded Presentation of PayPal's Express Checkout)
- PayPal_Pro (Enabler of PayPal Website Payments Pro)
- PayPal_Rest (Provider of Paypal's Rest API)




**For General Direction**

For comprehensive directives on application, kindly refer to the core [Omnipay](https://github.com/thephpleague/omnipay) repository.

## Peculiarities

The transaction reference garnered from the response of the purchase() function cannot be employed for the purpose of reimbursing a transaction. It is, in fact, the transaction reference originating from the response of the completePurchase() function that should be brought into play.

## Beyond the Horizon

Recurring payments or contractual invoicing agreements are outside the gamut of Omnipay's coverage, thus these attributes find no abode within this bundle. Welcoming are any augmentations to this gateway.


## Assistance

In the event of encountering general predicaments with Omnipay, we propose sharing your concerns on
[Stack Overflow](http://stackoverflow.com/). It is recommended to include the
[omnipay tag](http://stackoverflow.com/questions/tagged/omnipay) for convenient discoverability.

Should you aspire to remain abreast of release notifications, deliberate over project notions,
or pose more intricate inquiries, a [mailing list](https://groups.google.com/forum/#!forum/omnipay) is at your disposal
for subscription.

Should you harbor suspicions of having unearthed a glitch, we implore you to report it through the [GitHub issue tracker](https://github.com/thephpleague/omnipay-paypal/issues),
or, in an even more commendable endeavor, fork the repository and present a pull request.


Project Status
==============

This constitutes an Open Source initiative that stands as *vibrant*, yet within a state of *maintenance*. The
caretakers envision their primary obligations to encompass:

* rectifying any critical instances of data loss or security vulnerabilities.
* ensuring the project's synchronization with contemporary Django iterations (or other
  reliant components).
* expeditiously integrating skillfully crafted contributions from the community.

While the caretakers abstain from plotting grand-scale development undertakings and infusion of new functionalities,
certain pivotal segments within the code framework lack automated trials, possibly leading to impairment for certain Django or Python iterations. In the present scenario, these sectors of the codebase raise alerts, with the caretakers awaiting the kindness of the interested parties to offer indispensable trials and, where fitting, documentation.

It is imperative to recognize these nuances prior to lodging an issue. Should you stumble upon a flaw,
unless it corresponds to a grave data loss or security compromise, it is improbable that the caretakers will undertake complimentary efforts to rectify it. As for fresh attributes or trials for pre-existing functionalities, their inclusion hinges upon the caretakers' personal requirement.

Having said that, should you harbor substantial modifications earmarked for contribution, even encompassing extensive innovations (such as integration of newer PayPal payment methodologies), your endeavors will be enthusiastically embraced, provided they exhibit finesse in execution.

For further insights pertaining to leveraging the issue tracker and summoning pull requests, kindly consult `CONTRIBUTING.rst <CONTRIBUTING.rst>`_. For assistance queries, we kindly discourage the opening of issues.


Queries and Concerns
====================

In the eventuality of inquiries regarding the utilization of django-paypal, kindly direct your attention to the
`Discussion <https://github.com/spookylukey/django-paypal/discussions>`_ segment.
Reserved exclusively for addressing discrepancies or outlining novel enhancements that you wish to extend,
the `issues <https://github.com/spookylukey/django-paypal/issues>`_ section should be approached.


Paid Assistance
===============

Certain members of the caretaking team may extend paid support services for this
Open Source initiative. The services offered encompass the following realms:

* Financial remuneration for rectifying glitches or introducing fresh functionalities (with the understanding that these
  amendments will seamlessly integrate into the project and will not remain under the ownership of the contributor).

* Troubleshooting or alternative aid in assimilating django-paypal into your undertaking.

* Crafting the integration from scratch on your behalf.
