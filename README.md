# solid_principles_nd_design_patterns
Implementation of solid principles and most useful design patterns

1. Single Resp Principle Example
* Example:- Taxcalculator.new(employee) => We move out logic of tax calc from employee

2. Open closed Principle
* Example:- VehicleInsurance, HealthInsurance, HomeInsurance

3. Liskov Substitution Principle
* Example:- Ostrich Bird, Fly Interface

4. Interface Segregation Principle
* Example:- Print Copy Scan - Have smaller interfaces or small independent modules

5. Dependency Inversion/Dependency Injection
* Example:- Inject a low level dependency into class. ProductCatalog Class injecting ProductRepo class
* Payment example:- Stripe Payment, CreditCard Payment
* Have a common interface - order.pay(StripePayment.new)
* Abstractions should not depend upon details
