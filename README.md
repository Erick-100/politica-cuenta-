# politica-cuenta-
/**
 * Contrato que deben cumplir todas las políticas de cuentas bancarias.
 */
public interface PoliticaCuenta {

    String obtenerTipo();

    double calcularComisionTransferencia(double monto);

    double calcularInteresMensual(double saldo);
}
