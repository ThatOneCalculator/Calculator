import javax.swing.JOptionPane;
/**
 *
 * @author Kainoa Kanter (ThatOneCalculator)
 */
public class NewJFrame extends javax.swing.JFrame {
    public NewJFrame() {
        initComponents();
    }

    @SuppressWarnings("unchecked")                         
    private void initComponents() {

        firstNumberText = new javax.swing.JTextField();
        secondNumberText = new javax.swing.JTextField();
        jLabel1 = new javax.swing.JLabel();
        jLabel2 = new javax.swing.JLabel();
        plusButton = new javax.swing.JButton();
        minusButton = new javax.swing.JButton();
        answerLabel = new javax.swing.JLabel();
        divideButton = new javax.swing.JButton();
        multiplyButton = new javax.swing.JButton();
        powerButton = new javax.swing.JButton();
        modButton = new javax.swing.JButton();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);
        setTitle("Calculator");

        firstNumberText.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                firstNumberTextActionPerformed(evt);
            }
        });

        jLabel1.setText("1st number");

        jLabel2.setText("2nd number");

        plusButton.setText("Add");
        plusButton.setToolTipText("");
        plusButton.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                plusButtonActionPerformed(evt);
            }
        });

        minusButton.setText("Subtract");
        minusButton.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                minusButtonActionPerformed(evt);
            }
        });

        answerLabel.setFont(new java.awt.Font("Lucida Grande", 1, 18)); // NOI18N
        answerLabel.setText("Answer:");

        divideButton.setText("Divide");
        divideButton.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                divideButtonActionPerformed(evt);
            }
        });

        multiplyButton.setText("Multiply");
        multiplyButton.setToolTipText("");
        multiplyButton.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                multiplyButtonActionPerformed(evt);
            }
        });

        powerButton.setText("1st num²ⁿᵈ ⁿᵘᵐ");
        powerButton.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                powerButtonActionPerformed(evt);
            }
        });

        modButton.setText("Modulus");
        modButton.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                modButtonActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                .addContainerGap(68, Short.MAX_VALUE)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addComponent(powerButton)
                        .addGap(18, 18, 18)
                        .addComponent(modButton))
                    .addGroup(layout.createSequentialGroup()
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING, false)
                                .addComponent(firstNumberText, javax.swing.GroupLayout.Alignment.LEADING)
                                .addComponent(jLabel1, javax.swing.GroupLayout.Alignment.LEADING))
                            .addGroup(layout.createSequentialGroup()
                                .addComponent(plusButton)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                .addComponent(minusButton)))
                        .addGap(3, 3, 3)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(layout.createSequentialGroup()
                                .addGap(83, 83, 83)
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                    .addComponent(jLabel2, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                    .addComponent(secondNumberText, javax.swing.GroupLayout.PREFERRED_SIZE, 76, javax.swing.GroupLayout.PREFERRED_SIZE)))
                            .addGroup(layout.createSequentialGroup()
                                .addGap(9, 9, 9)
                                .addComponent(multiplyButton)
                                .addGap(18, 18, 18)
                                .addComponent(divideButton)))))
                .addGap(56, 56, 56))
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(answerLabel)
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel1)
                    .addComponent(jLabel2))
                .addGap(18, 18, 18)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(secondNumberText, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(firstNumberText, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(40, 40, 40)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(plusButton)
                    .addComponent(minusButton)
                    .addComponent(multiplyButton)
                    .addComponent(divideButton))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(powerButton)
                    .addComponent(modButton))
                .addGap(18, 18, 18)
                .addComponent(answerLabel, javax.swing.GroupLayout.DEFAULT_SIZE, 115, Short.MAX_VALUE)
                .addGap(33, 33, 33))
        );

        pack();
    }// </editor-fold>                        

    private void firstNumberTextActionPerformed(java.awt.event.ActionEvent evt) {
        // Legit nothing has to be here
    }

    private void plusButtonActionPerformed(java.awt.event.ActionEvent evt) {
        double number1, number2;
        try {
            number1 = Double.parseDouble(
                    this.firstNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 1st number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        try {
            number2 = Double.parseDouble(
                    this.secondNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 2nd number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        double answer;
        answer = number1 + number2;
        this.answerLabel.setText("Answer: " + Math.round(answer * 10000) / 10000.0);
    }

    private void minusButtonActionPerformed(java.awt.event.ActionEvent evt) {
        double number1, number2;
        try {
            number1 = Double.parseDouble(
                    this.firstNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 1st number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        try {
            number2 = Double.parseDouble(
                    this.secondNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 2nd number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        double answer;
        answer = number1 - number2;
        this.answerLabel.setText("Answer: " + Math.round(answer * 10000) / 10000.0);
    }

    private void divideButtonActionPerformed(java.awt.event.ActionEvent evt) {
        double number1, number2;
        try {
            number1 = Double.parseDouble(
                    this.firstNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 1st number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        try {
            number2 = Double.parseDouble(
                    this.secondNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 2nd number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        double answer;
        answer = number1 / number2;
        this.answerLabel.setText("Answer: " + Math.round(answer * 10000) / 10000.0);
    }

    private void multiplyButtonActionPerformed(java.awt.event.ActionEvent evt) {
        double number1, number2;
        try {
            number1 = Double.parseDouble(
                    this.firstNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 1st number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        try {
            number2 = Double.parseDouble(
                    this.secondNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 2nd number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        double answer;
        answer = number1 * number2;
        this.answerLabel.setText("Answer: " + Math.round(answer * 10000) / 10000.0);
    }

    private void powerButtonActionPerformed(java.awt.event.ActionEvent evt) {
        double number1, number2;
        try {
            number1 = Double.parseDouble(
                    this.firstNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 1st number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        try {
            number2 = Double.parseDouble(
                    this.secondNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 2nd number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        double answer;
        answer = Math.pow(number1, number2);
        this.answerLabel.setText("Answer: " + Math.round(answer * 10000) / 10000.0);    }

    private void modButtonActionPerformed(java.awt.event.ActionEvent evt) {                                          
        double number1, number2;
        try {
            number1 = Double.parseDouble(
                    this.firstNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 1st number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        try {
            number2 = Double.parseDouble(
                    this.secondNumberText.getText());
        } catch (NumberFormatException e) {
            JOptionPane.showMessageDialog(this, "Bad 2nd number", "Error", JOptionPane.ERROR_MESSAGE);
            return;
        }
        double answer;
        answer = number1 % number2;
        this.answerLabel.setText("Answer: " + Math.round(answer * 10000) / 10000.0);
    }                                         

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException | InstantiationException | IllegalAccessException | javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(NewJFrame.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(() -> {
            new NewJFrame().setVisible(true);
        });
    }                   
    private javax.swing.JLabel answerLabel;
    private javax.swing.JButton divideButton;
    private javax.swing.JTextField firstNumberText;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JLabel jLabel2;
    private javax.swing.JButton minusButton;
    private javax.swing.JButton modButton;
    private javax.swing.JButton multiplyButton;
    private javax.swing.JButton plusButton;
    private javax.swing.JButton powerButton;
    private javax.swing.JTextField secondNumberText;
    // End of variables declaration                   
}
