# VendPheatBundle
### Symfony2 Integration for the Pheat feature manager

This bundle integrates Pheat, a feature manager, with Symfony2. It provides
you with the ability to activate features based on dynamic configuration, and
provide them to flexible subsets of your users and tenants.

Still with me?

A typical feature rollout might involve:

- Deploying the feature completely deactivated for everybody
- Allowing some internal developers (with a role assigned) access to the feature
- Allowing some beta testers access to the feature
- Activating the feature for 1% of users, with feedback into your monitoring and analytics systems
- Activating the feature for 10%, 30% then 100% of customers
- Having the feature enabled long-term, but with the ability to turn it off at any time

The idea is to use commits and developer time for as little of this as possible, and to
make the whole thing 'push-button' easy.

To that end, this bundle will provide a UI for feature management that can be integrated into your
backend toolset, and several Symfony-native integration points for the feature manager itself.

## Documentation

The bulk of the documentation is stored in the `Resources/doc/index.md` file in this bundle:

[Read the Documentation for master](https://github.com/vend/VendPheatBundle/blob/master/Resources/doc/index.md)

## Credits

* Icon made by [Picol](http://picol.org) from [flaticon.com](http://www.flaticon.com)
  is licensed under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/)