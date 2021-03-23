# DOM Atomic 05: Toggle Elements of DOM Path

## Questions

---

> Describe the contract you used for finding the movies to toggle in the DOM. How is this function different from other functions that find elements in the DOM?

Tā vietā, lai izmantotu .getElementsByClassName(), es izmantoju .querySelectorAll(). .getElementsByClassName() prasa tikai vienu argumentu, tāpēc īsti nevar strādāt, bet .querySelectorAll() ļauj precizēt.