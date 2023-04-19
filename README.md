# Enum-week-

enum Week{

    A, B, C;

}

class Day {

public static void main(String... args){

    Week w1=Week.A;

    Week w2 = Week.B;

    Week w3= Week.C;

    System.out.println(w1+" "+w2+ " "+w3 );

    

        Week [] w=Week.values();

        for(Week ww:w){

            System.out.println(ww);

        }

    }

}
