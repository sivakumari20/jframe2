# jframe2   ***JBUTTON***
package gui;
import javax.swing.JFrame;
import javax.swing.event.AncestorListener;

import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

import javax.swing.JButton;

public class frame1 extends JFrame  implements ActionListener {
	JButton button;

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		//frame1 =a button that performs an action when clicked on
		
	JButton button=new JButton();
	button.setBounds(200,100,100,50);
	
    frame1 frame=new frame1();
    JFrame frame11=new JFrame();// creates a new frame
	frame11.setTitle("Sieve frame");//set frame title
	frame11.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	frame11.setLayout(null);
	frame11.setSize(100, 100); //set x and y coordinates of frame
	frame11.setVisible(true);
	frame11.add(button);
	frame11.add(button);
	 //button.addContainerListener( frame11);
    
		}

	

	@Override
	public void actionPerformed(ActionEvent e) {
		// TODO Auto-generated method stub
		if(e.getSource()==button) {
			System.out.println("loooo");
			
		}
		
	}

}
