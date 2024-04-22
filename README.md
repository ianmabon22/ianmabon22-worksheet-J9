# ianmabon22-worksheet-J9
1. A java library is prewritten code that serves a functional purpose while design patterns are the way the code is implemented that makes it more robust or efficient.
2. private Instance() {contruction objects} -> public static getInstance() { if(instance == null) { instance = new Instance() } return instance; }
3. public static Animal getAnimal() (String type, String name, int weight) switch(type) case("Bird") return new Bird(name, weight) case("Mammal") return new Mammal(name, weight)
4. public class MammalAdapter extends Fish { private Mammal m; public MammalAdapter(Mammal mammal) { mammal = m; } public void feed(String food, int weight, String medication) {return mammal.feed(String f, int w, String m)} public void clean(String c) {return mammal.clean()}
5. Aggregates code into a parent interface in order to reduce code repetition when adding new object types with similar interfaces.
   
