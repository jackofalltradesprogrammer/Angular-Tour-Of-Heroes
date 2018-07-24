# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.The Tour of Heroes tutorial covers the fundamentals of Angular. In this tutorial you will build an app that helps a staffing agency manage its stable of heroes.

This basic app has many of the features you'd expect to find in a data-driven application. It acquires and displays a list of heroes, edits a selected hero's detail, and navigates among different views of heroic data.

## 1. The Application Shell

You created the initial application structure using the Angular CLI.
You learned that Angular `components` display data.
You used the `double curly braces of interpolation` to display the app title

## 2. The Hero Editor

You used the CLI to create a second `HeroesComponent`.
You displayed the `HeroesComponent` by adding it to the `AppComponent` shell.
You applied the `UppercasePipe` to format the name.
You used two-way data binding with the `ngModel` directive.
You learned about the `AppModule`.
You imported the `FormsModule` in the `AppModule` so that Angular would recognize and apply the `ngModel` directive.
You learned the importance of declaring components in the `AppModule` and appreciated that the CLI declared it for you.

## 3. Displaying a list

The Tour of Heroes app displays a list of heroes in a Master/Detail view.
The user can select a hero and see that hero's details.
You used `*ngFor` to display a list.
You used `*ngIf` to conditionally include or exclude a block of HTML.
You can toggle a CSS style class with a `class` binding.

## 4. Master/Detail Components
You created a separate, reusable `HeroDetailComponent`.
You used a `property binding` to give the parent `HeroesComponent` control over the child `HeroDetailComponent`.
You used the `@Input decorator` to make the hero property available for binding by the external `HeroesComponent`.

## 5. Services

You refactored data access to the `HeroService` class.
You registered the `HeroService` as the provider of its service at the root level so that it can be injected anywhere in the app.
You used `Angular Dependency Injection` to inject it into a component.
You gave the `HeroService` get data method an asynchronous signature.
You discovered `Observable` and the RxJS Observable library.
You used RxJS `of()` to return an observable of mock heroes (`Observable<Hero[]>`).
The component's `ngOnInit` lifecycle hook calls the `HeroService` method, not the constructor.
You created a `MessageService` for loosely-coupled communication between classes.
The `HeroService` injected into a component is created with another injected service, `MessageService`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
