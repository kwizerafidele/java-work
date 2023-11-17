public class For {
    public static void main(String[] args) {
        String[] towns = {
                "rwamagana",
                "musanze",
                "gasaka",
                "muhanga",
                "gitarama",
                "ngororero"
        };

        System.out.println("favorite towns..");

        for (int i = 0; i < towns.length; i++) {
            String town= towns[i];
            if (town.equals("rwamagana")) {
                System.out.println("welcome to rwamagana");
            } else {
                System.out.println("welcome"    +town+   "and enjoy ");
            }
        }

        System.out
                .println(" welcome All " +towns.length + " enjoy our scenery cities");
    }
}
