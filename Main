import java.io.*;

public class Main {

    public static void main(String[] args) throws IOException {

        //method of generate numbers
        generatingNumbers("C:\\Users\\win\\OneDrive\\testFile.txt");

        //method of reading numbers
        readingNumbers("C:\\Users\\win\\OneDrive\\testFile.txt");

    }

    public static void generatingNumbers(String filePath) throws IOException {

        File file = new File(filePath);
        FileWriter fw = new FileWriter(file);

        for (int i = 1; i < 1000+1; i++) {
            fw.write(i + "\n");
        }

        fw.close();

    }

    public static void readingNumbers(String filePath) throws IOException {

        BufferedReader br = new BufferedReader(new FileReader(filePath));

        String line;

        while ((line = br.readLine()) != null) {
            System.out.println(line);
        }

    }
}
