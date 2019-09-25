# If-Else-practice


package academy.learnprograming;

import org.w3c.dom.ls.LSOutput;

import javax.swing.*;

public class Main {

    public static void main(String[] args) {

    newscoremethod(true, 500, 5 , 100);
    newscoremethod(false, 800,5,100);
    }

    public static int newscoremethod ( boolean GameOver, int score , int levelCompleted, int bonus) {

        if (GameOver) {
            int finalscore = score + (levelCompleted * bonus);
            finalscore += 1000;
            System.out.println("Final Score is " + finalscore);
            return finalscore;
        }

            return -1;
    }
}
