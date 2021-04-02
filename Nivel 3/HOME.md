# Nivel 3

![diagram](https://www.plantuml.com/plantuml/svg/0/hLRDRjiu4Bu7o3jmVOaBh2eqJYvxgckxhG7RSMDtWpqPjCJOQYbIbIWxxY8FizZ3FaXUR6SeIY5boKs1-k3GdFdcv-Fyv6scQAhoc9-V_HQ9WESX8rkbakmFtq_f_lKcKjjydMSi3QHGJAZNWOnz6gOH5JkU9xa_kFBcd0hrUJhnELKiKt2r6hA4oqECWAIm7hBxI30o7Fqv7jpC5Y_mel847FNy1Cs34Iy2gNSF6bwMf16uycEQAPRw8TkXB7jsy_vcjkpVZHOtqz4lzQJlw9vbCcRUjKLQcPTFnIRdD2tJFf9_eJlQAamEQYj5gpYMOYF3TRiy-yPNaDkE7Vct2F4n_Smed9zD-d_TV5wkxiRBZwl9wCDeDko-mliBeYB56S4dPIS-g3i7Wr9q0nu1fUntqXaKfmuSpINXSaD3IGGbDE5HG0CgKQo3wO37nG7ynDraJ-5sVjT78Ni0qWNbU3R4TdHm8x2OmjDaRFLEvYAawQ4BFtVW0LJDgVEA_7r-Hk1Js5wD7bIN9X5ezETZSWk9eU54Iaw08f1Sw4W0eByCgd8GK4KX2_a64pHduf4robbw8Bga7XIw9RRV2dXfF9TWz4wCHp80D8NQJOVh2j03XPbSVDC4JF7rXsiyMWzTmgqKI_GLnZcSELvk6LyDxO1iLof8RBs9RSdMqnrbD1_nEHh8IkY6OlzhjkRbZnVHLK6HhmymK_RqGAhB8Xtumavg8g_IxBN37JPiVmwO_2178LLqNvJo6_rIrS-MF9qqBVIbXNxwx-dVvoIBYT3mo1OQGrtk8yurR4eZJcAQVcKg4flJIAoGOPGbD9L9gj6BwU8qvDeALKLIa8-vBibvdcs9i0IbcGjZw5FESbQd3Bl1egqHKu_WyXIkAeGZTxsNmvfeQe4-4Zqj7CQg-c11Z4cE1bEeXv7Ou6P2JoaCdAaCSvYk9_kXh1ImStdQZbFLJZS0jlSpM6o9M-FHOCrOS6BI584SgHdBPLa5O8UGSdu-wcym-6pkglIbMyeCet9h5AE_6YwcEV6o6DerYRwqHskJt9abJGgrmcfICVHNebBeGckbLZFKgdlr4xhNRXIuevstXcW7DDZg1On_gocYARyW3Ikfhvc5XVJqJxcHZdIj20hrer5r11biMV1rBFGVcHid-CEB1F59SPIvthyfmqr6eVvZagJCexcIQVJTMAzRXa8kpC71TMqp0S8XPAXZzHQV9arCD2rSKCKXs0omAX_MwZikr-EORbXMMxDEk5Nz5K7FxJNK74g5Q8a5CTXJJOrHIFIbLGkcVorXHM8JqYsDceOZT5bpt3XwTRPgDbsEQlaxLbtDfY8xphL9gnP0ISTprJXc6YmSjOG3AEsrQPsVlMKYXF-__mS0)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.