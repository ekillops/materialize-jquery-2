export default Ember.Route.extend({
  actions: {
    didInsertElement() {
      Ember.$(".button-collapse").sideNav();
    }
  }
