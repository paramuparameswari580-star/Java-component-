class ExtractName {
    public static void main(String[] args) {
        String username = "Parameswari";
        int n = 5;  
        String shortName = username.substring(0, n);
        System.out.println("Original Name: " + username);
        System.out.println("Displayed Name: " + shortName);
    }
}
