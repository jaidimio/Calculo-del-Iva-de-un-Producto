# Calculo-del-Iva-de-un-Producto
// Para este ejercicio tendréis que crear una función que reciba un precio y devuelva el precio con el IVA incluido.//

// creación del paquete
package com.CalculoIva;

//clase para hacer el calculo
public class SaberIva {
    private static double precio = 1500;

    public static void main (String [] args) {
        double SaberIva = iva (1500*.19);
        double resultado = total (SaberIva + precio);
        System.out.println ("El Iva del Producto es:  " + SaberIva);
        System.out.println ("El Precio Total del Producto es: "  + resultado);

    }

    private static double total(double v) {
        return v;
    }

    static double iva(double SaberIva) {
        return SaberIva;
    }
    public double iva;
// la función
    public double SaberIva () {
        iva = precio * (.19);
        return iva;
    }

    }
