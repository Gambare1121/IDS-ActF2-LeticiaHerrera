public class Main {
    public static void main(String[] args) {
        // 4. Instanciación de Objetos
        Empleado emp1 = new Empleado("Ana Martínez", "Gerente de Ventas", 25000);
        Empleado emp2 = new Empleado("Luis Pérez", "Analista de Datos", 18000);

        // 5. Prueba de Métodos
        System.out.println("--- Estado Inicial ---");
        emp1.mostrarDetalles();
        emp2.mostrarDetalles();

        System.out.println("\n--- Aplicando Incentivos ---");
        emp1.aplicarBono(10); // Bono del 10%
        
        System.out.println("\n--- Estado Final ---");
        emp1.mostrarDetalles();
    }
}
