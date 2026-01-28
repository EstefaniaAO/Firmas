
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


# Firmas 8-14
```csharp
public static void MostrarNumeroEntero(int numero)
{
}

public static double Multiplicar(double a, double b)
{
    return 0.0;
}

public static string UnirCadenas(string a, string b)
{
    return "";
}

public static bool EsMayor(int a, int b)
{
    return false;
}

public static int ContarElementos(int[] arreglo)
{
    return 0;
}

public static int[,] CrearMatriz(int filas, int columnas)
{
    return new int[0,0];
}

public static char ObtenerPrimerCaracter(string texto)
{
    return ' ';
}
```
# Invocaciones de las funciones/metodos
```csharp
static void Main(string[] args)
{
    MostrarNumeroEntero(7);

    double producto = Multiplicar(2.5, 3.0);

    string unido = UnirCadenas("Hola", " Mundo");

    bool mayor = EsMayor(10, 5);

    int[] numeros = { 1, 2, 3 };
    int cantidad = ContarElementos(numeros);

    int[,] matriz = CrearMatriz(2, 2);

    char letra = ObtenerPrimerCaracter("ChatGPT");
}
```
