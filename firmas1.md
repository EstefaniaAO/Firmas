
# Firmas 1-7
```csharp
public static void Saludar()
{
}

public static int Sumatoria(int num1, int num2)
{
    return 0;
}

public static double CalcularPromedio(int[] numeros)
{
    return 0.0;
}

public static bool EsPar(int numero)
{
    return false;
}

public static string ConvertirAMayuscula(string texto)
{
    return "";
}

public static int[] InvertirArray(int[] arreglo)
{
    return new int[0];
}


public static void MostrarMensaje(string mensaje)
{
}
```
# Invocaciones de las funciones/metodos
```csharp
static void Main(string[] args)
{
    Saludar();

    int resultadoSuma = Sumar(4, 4);

    int[] valores = { 1, 2, 3, 4, 5 };
    double promedio = CalcularPromedio(valores);

    bool par = EsPar(10);
    string texto = ConvertirAMayuscula("holas");
    int[] invertido = InvertirArray(valores);

    MostrarMensaje("explicamos firmas");
}
```
