class Person {
    constructor(name = 'Tom', age = 20, energy = 100) {
        this.name = name;
        this.age = age;
        this.energy = energy;
    }
    sleep() {
        if (this.energy += 10);

    }
    doSomethingFun() {
        if (this.energy -= 10);
    }


}

class Worker extends Person {
    constructor(name, age, energy, xp = 0, hourlyWage = 10) {
        super(name, age, energy)
    }
    goToWork() {
        if (this.xp + 10);
    }
}
function intern() {
    var intern = new Worker('Bob', 21, 110, 0, 10);
    return intern;
}
function manager() {
    var manager = new Worker('Alice', 30, 120, 100, 30);
    return manager;
}
intern();
manager();
