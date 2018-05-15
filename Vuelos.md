# Cantera-
package javaapplication65;

import java.text.DateFormat;
import java.text.SimpleDateFormat;
import java.util.ArrayList;
import java.util.Date;

public class Vuelos {

    public static void main(String[] args) {
        Consultar cosult = new Consultar();
        cosult.consultaVuelo("2018", "06", "11");
    }

}
