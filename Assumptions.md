# School Admission System

As it will have a huge traffic on the get request I wanted to use CQRS pattern in module.
which will help to manage traffic as the get and post methods are used in different modules.

But another problem arise that same time seat reservation requesting which I think I can solve
using persimesstic locking . So that It will lock then hold for sometimes to confirm it then It will unhold it.