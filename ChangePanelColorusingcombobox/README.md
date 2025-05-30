# Change Panel Color using combo box🎨
A simple Java Swing app that changes the color of a panel using a combo box.

 Demo
[Watch on YouTube](https://youtube.com/shorts/noHS7FT0T6g?feature=share)
💻 How to Run
1. Make sure you have downloaded netbeans
2. create simple gui
3. Copy this code
private void changeColor() {
        String selectedColor = (String) cmbbox1.getSelectedItem();
        switch (selectedColor) {
            case "RED":
                panel1.setBackground(Color.RED);
                break;
            case "GREEN":
                panel1.setBackground(Color.GREEN);
                break;
            case "BLUE":
                panel1.setBackground(Color.BLUE);
                break;
                case "PINK":
                panel1.setBackground(Color.PINK);
                break;
                case "YELLOW":
                panel1.setBackground(Color.YELLOW);
                break;
                case "ORANGE":
                panel1.setBackground(Color.ORANGE);
                break;
                case "BLACK":
                panel1.setBackground(Color.BLACK);
                break;
            default:
                panel1.setBackground(Color.WHITE);
                break;
        }
    }
    private void cmbbox1ActionPerformed(java.awt.event.ActionEvent evt) {                                        

          changeColor();  
      
    }     
