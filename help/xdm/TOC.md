---
product: experience-platform
audience: user
user-guide-title: Experience Data Model (XDM) System Help
breadcrumb-title: Data Model (XDM) Guide
user-guide-description: Use Experience Data Model (XDM) classes and mixins to standardize experience data.
---

# Experience Data Model (XDM) System {#xdm}

* [XDM System overview](home.md)
* Schemas {#schema}
  * [Basics of schema composition](schema/composition.md)
  * [XDM field type constraints](schema/field-constraints.md)
  * [XDM field dictionary](schema/field-dictionary.md)
  * Schema use cases {#use-cases}
    * [Privacy Consent mixin](schema/privacy-consent.md)
* Classes {#classes}
  * [XDM Individual Profile](./classes/individual-profile.md)
  * [XDM ExperienceEvent](./classes/experienceevent.md)
* Mixins {#mixins}
  * Profile mixins {#profile}
    * [IdentityMap](./mixins/profile/identitymap.md)
    * [Demographic Details](./mixins/profile/person-details.md)
    * [Personal Contact Details](./mixins/profile/personal-details.md)
    * [Segment Membership Details](./mixins/profile/segmentation.md)
    * [Work Contact Details](./mixins/profile/work-details.md)
  * Event mixins {#event}
    * [End User ID Details](./mixins/event/enduserids.md)
    * [Environment Details](./mixins/event/environment-details.md)
  * [Mixin name updates](./mixins/name-updates.md)
* Data types {#data-types}
    * [Beacon](./data-types/beacon.md)
    * [Browser details](./data-types/browser-details.md)
    * [Device](./data-types/device.md)
    * [Email address](./data-types/email-address.md)
    * [Environment](./data-types/environment.md)
    * [Geo](./data-types/geo.md)
    * [Geo Circle](./data-types/geo-circle.md)
    * [Geo coordinates](./data-types/geo-coordinates.md)
    * [Geo interaction details](./data-types/geo-interaction-details.md)
    * [Geo Shape](./data-types/geo-shape.md)
    * [Identity](./data-types/identity.md)
    * [Person name](./data-types/person-name.md)
    * [Phone number](./data-types/phone-number.md)
    * [Place context](./data-types/place-context.md)
    * [POI details](./data-types/poi-details.md)
    * [POI interaction](./data-types/poi-interaction.md)
    * [Postal address](./data-types/postal-address.md)
* Schema Registry API {#api}
  * [Getting started](api/getting-started.md)
  * [List resources](api/list-resources.md)
  * [Look up a resource](api/look-up-resource.md)
  * [Update a resource](api/update-resource.md)
  * [Replace a resource](api/replace-resource.md)
  * [Delete a resource](api/delete-resource.md)
  * [Create a class](api/create-class.md)
  * [Create a mixin](api/create-mixin.md)
  * [Create a data type](api/create-data-type.md)
  * [Create a schema](api/create-schema.md)
  * [Unions](api/unions.md)
  * [Descriptors](api/descriptors.md)
  * [Ad-hoc schemas](api/ad-hoc.md)
  * [Appendix](api/appendix.md)
* Tutorials {#tutorials}
  * [Create a schema (API)](tutorials/create-schema-api.md)
  * [Create a schema (UI)](tutorials/create-schema-ui.md)
  * [Define a relationship between two schemas (API)](tutorials/relationship-api.md)
  * [Define a relationship between two schemas (UI)](tutorials/relationship-ui.md)
  * [Create an ad-hoc schema (API)](tutorials/ad-hoc.md)
* [Troubleshooting guide](troubleshooting-guide.md)
* [API reference](https://www.adobe.io/apis/experienceplatform/home/api-reference.html#!acpdr/swagger-specs/schema-registry.yaml)
* [Platform release notes](https://www.adobe.com/go/platform-release-notes-en)