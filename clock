// Simple Digital Clock in Java using Swing
import javax.swing.*;
import java.awt.*;
import java.text.SimpleDateFormat;
import java.util.Date;
public class DigitalClock extends JFrame {
 private JLabel timeLabel;
 DigitalClock() {
 // Set up the frame
 setTitle("Digital Clock");
 setSize(300, 100);
 setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
 setLayout(new FlowLayout());
 // Create the label to display time
 timeLabel = new JLabel();
 timeLabel.setFont(new Font("Verdana", Font.PLAIN, 30));
 add(timeLabel);
 // Timer to update the clock every second
 Timer timer = new Timer(1000, e -> updateClock());
 timer.start();
 // Initial update and show the window
 updateClock();
 setVisible(true);
 }
 private void updateClock() {
 // Get current time and format it
 SimpleDateFormat formatter = new SimpleDateFormat("HH:mm:ss");
 String time = formatter.format(new Date());
 timeLabel.setText(time);
 }
 public static void main(String[] args) {
 new DigitalClock();
 }
}
