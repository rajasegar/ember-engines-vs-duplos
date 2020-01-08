# ember-engines-vs-duplos

With Ember engines you're typically setting out to build an app, usually a large app
and you break it down into smaller pieces so that independent teams can build these
features and experiences and then you can bring them back together to ship your app and
not only that these engines are actually in a little isolated container so they're really
hard for the application, the host application to customize the engine.

But with Duplos we are building foundational pieces that can be composed to build
not just one app but several apps and these apps might not look the same, not only
that but these duplos can be customized to fit the needs of the individual application because as 
we know each app is a snowflake with its own requirements, stakeholders and special sauce.

## Ember Engines
[Ember Engines](http://ember-engines.com/)

## Duplos
Duplos is a new pattern followed in Yahoo for managing modular monoliths. 
Watch [Jon Kilroy](https://github.com/jkusa)'s talk in Ember Fest about [Duplos](https://www.youtube.com/watch?v=7K4Gkr_w58w)
Slides [here](https://slides.com/jkusa/ember-duplos)

## Comparison

| Capabilities          | Engines       | Duplos|
| ----------------------|:-------------:| -----:|
| Code Isolation        | Yes | Yes |
| Lazy Loading          | Yes      |   No |
| Re-usability          | No       |    Yes |
| Autonomous Deployment | Yes      |   Yes  |
| Routable              | Yes       |    Yes |

