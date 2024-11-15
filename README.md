
# Aplikasi Pertambahan Dua Angka



# Deskripsi
Aplikasi ini merupakan aplikasi pertambahan dua angka dengan menggunakan komponen JFrame  untuk membangun antarmuka pengguna yang interaktif. Pengguna dapat memasukkan angka yang ingin di tambahkan melalui JTextField kemudian untuk mengetahui hasil dari angka yang sudah di memasukkan, pengguna dapat menekan tombol JButton yang bertuliskan "Tambah" dan terdapat tombol "Hapus" untuk menghapus angka dan ada tombol "keluar" untuk keluar dari aplikasi
## Features

Fitur utama aplikasi ini meliputi:
- Input Dua Angka: Pengguna dapat memasukkan dua angka pada kolom input yang tersedia.
- Tombol Tambah: Menghitung dan menampilkan hasil penjumlahan dari dua angka yang diinput.
- Tombol Hapus: Menghapus semua input yang ada di kolom input dan hasil, serta mengembalikan fokus ke kolom input pertama.
- Tombol Keluar: Menutup aplikasi.


        # Code

```
        import javax.swing.JOptionPane;

        /*
        * To change this license header, choose License Headers in Project Properties.
        * To change this template file, choose Tools | Templates
        * and open the template in the editor.
        */

        /**
        *
        * @author Putra
        */
        public class FormTambahAngka extends javax.swing.JFrame {

            /**
            * Creates new form FormTambahAngka
            */
            public FormTambahAngka() {
                initComponents();
            }

            /**
            * This method is called from within the constructor to initialize the form.
            * WARNING: Do NOT modify this code. The content of this method is always
            * regenerated by the Form Editor.
            */
            @SuppressWarnings("unchecked")
            // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
            private void initComponents() {

                jPanel2 = new javax.swing.JPanel();
                jLabel5 = new javax.swing.JLabel();
                jLabel6 = new javax.swing.JLabel();
                jLabel7 = new javax.swing.JLabel();
                txtAngka1 = new javax.swing.JTextField();
                txtAngka2 = new javax.swing.JTextField();
                txtHasil = new javax.swing.JTextField();
                jButton1 = new javax.swing.JButton();
                jButton2 = new javax.swing.JButton();
                jButton3 = new javax.swing.JButton();
                jLabel1 = new javax.swing.JLabel();

                setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

                jLabel5.setFont(new java.awt.Font("Times New Roman", 1, 18)); // NOI18N
                jLabel5.setText("Masukkan Angka");

                jLabel6.setFont(new java.awt.Font("Times New Roman", 1, 24)); // NOI18N
                jLabel6.setText("+");

                jLabel7.setFont(new java.awt.Font("Times New Roman", 1, 24)); // NOI18N
                jLabel7.setText("=");

                txtAngka1.addFocusListener(new java.awt.event.FocusAdapter() {
                    public void focusGained(java.awt.event.FocusEvent evt) {
                        txtAngka1FocusGained(evt);
                    }
                });
                txtAngka1.addActionListener(new java.awt.event.ActionListener() {
                    public void actionPerformed(java.awt.event.ActionEvent evt) {
                        txtAngka1ActionPerformed(evt);
                    }
                });
                txtAngka1.addKeyListener(new java.awt.event.KeyAdapter() {
                    public void keyTyped(java.awt.event.KeyEvent evt) {
                        txtAngka1KeyTyped(evt);
                    }
                });

                txtAngka2.addKeyListener(new java.awt.event.KeyAdapter() {
                    public void keyTyped(java.awt.event.KeyEvent evt) {
                        txtAngka2KeyTyped(evt);
                    }
                });

                jButton1.setBackground(new java.awt.Color(153, 204, 255));
                jButton1.setFont(new java.awt.Font("Tahoma", 1, 13)); // NOI18N
                jButton1.setText("Tambah");
                jButton1.setCursor(new java.awt.Cursor(java.awt.Cursor.HAND_CURSOR));
                jButton1.addActionListener(new java.awt.event.ActionListener() {
                    public void actionPerformed(java.awt.event.ActionEvent evt) {
                        jButton1ActionPerformed(evt);
                    }
                });

                jButton2.setBackground(new java.awt.Color(153, 204, 255));
                jButton2.setFont(new java.awt.Font("Tahoma", 1, 13)); // NOI18N
                jButton2.setText("Hapus");
                jButton2.setCursor(new java.awt.Cursor(java.awt.Cursor.HAND_CURSOR));
                jButton2.addActionListener(new java.awt.event.ActionListener() {
                    public void actionPerformed(java.awt.event.ActionEvent evt) {
                        jButton2ActionPerformed(evt);
                    }
                });

                jButton3.setBackground(new java.awt.Color(153, 204, 255));
                jButton3.setFont(new java.awt.Font("Tahoma", 1, 13)); // NOI18N
                jButton3.setText("Keluar");
                jButton3.setCursor(new java.awt.Cursor(java.awt.Cursor.HAND_CURSOR));
                jButton3.addActionListener(new java.awt.event.ActionListener() {
                    public void actionPerformed(java.awt.event.ActionEvent evt) {
                        jButton3ActionPerformed(evt);
                    }
                });

                jLabel1.setFont(new java.awt.Font("Times New Roman", 1, 24)); // NOI18N
                jLabel1.setHorizontalAlignment(javax.swing.SwingConstants.CENTER);
                jLabel1.setText("Aplikasi Pertambahan Dua Angka");

                javax.swing.GroupLayout jPanel2Layout = new javax.swing.GroupLayout(jPanel2);
                jPanel2.setLayout(jPanel2Layout);
                jPanel2Layout.setHorizontalGroup(
                    jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel2Layout.createSequentialGroup()
                        .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel2Layout.createSequentialGroup()
                                .addGap(96, 96, 96)
                                .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                                    .addComponent(jLabel5)
                                    .addGroup(jPanel2Layout.createSequentialGroup()
                                        .addComponent(txtAngka1, javax.swing.GroupLayout.PREFERRED_SIZE, 58, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                        .addComponent(jLabel6)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                        .addComponent(txtAngka2, javax.swing.GroupLayout.PREFERRED_SIZE, 58, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addGap(18, 18, 18)
                                        .addComponent(jLabel7)))
                                .addGap(18, 18, 18)
                                .addComponent(txtHasil, javax.swing.GroupLayout.PREFERRED_SIZE, 58, javax.swing.GroupLayout.PREFERRED_SIZE))
                            .addGroup(jPanel2Layout.createSequentialGroup()
                                .addGap(92, 92, 92)
                                .addComponent(jButton1)
                                .addGap(18, 18, 18)
                                .addComponent(jButton2, javax.swing.GroupLayout.PREFERRED_SIZE, 81, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                                .addComponent(jButton3, javax.swing.GroupLayout.PREFERRED_SIZE, 79, javax.swing.GroupLayout.PREFERRED_SIZE)))
                        .addContainerGap(138, Short.MAX_VALUE))
                    .addComponent(jLabel1, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                );
                jPanel2Layout.setVerticalGroup(
                    jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(jPanel2Layout.createSequentialGroup()
                        .addComponent(jLabel1, javax.swing.GroupLayout.PREFERRED_SIZE, 58, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(44, 44, 44)
                        .addComponent(jLabel5)
                        .addGap(18, 18, 18)
                        .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                                .addComponent(jLabel6)
                                .addComponent(txtAngka1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                            .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                                .addComponent(txtAngka2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addComponent(jLabel7)
                                .addComponent(txtHasil, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)))
                        .addGap(37, 37, 37)
                        .addGroup(jPanel2Layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(jButton1)
                            .addComponent(jButton2)
                            .addComponent(jButton3))
                        .addContainerGap(105, Short.MAX_VALUE))
                );

                javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
                getContentPane().setLayout(layout);
                layout.setHorizontalGroup(
                    layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addContainerGap()
                        .addComponent(jPanel2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                );
                layout.setVerticalGroup(
                    layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addContainerGap()
                        .addComponent(jPanel2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                );

                pack();
            }// </editor-fold>                        

            private void txtAngka1ActionPerformed(java.awt.event.ActionEvent evt) {                                          
                    // TODO add your handling code here:
            }                                         

            private void jButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                         
                txtAngka1.setText("");
                txtAngka2.setText("");
                txtHasil.setText("");
                txtAngka1.requestFocus();        // TODO add your handling code here:
            }                                        

            private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
                {
            try {
                int angka1 = Integer.parseInt(txtAngka1.getText());
                int angka2 = Integer.parseInt(txtAngka2.getText());
                int hasil = angka1 + angka2;
                txtHasil.setText(String.valueOf(hasil));
            } catch (NumberFormatException e) {
                JOptionPane.showMessageDialog(this, "Masukkan angka yang valid", "Error", JOptionPane.ERROR_MESSAGE);
            }
        }
                // TODO add your handling code here:
            }                                        

            private void jButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                         
                System.exit(0);        // TODO add your handling code here:
            }                                        

            private void txtAngka1KeyTyped(java.awt.event.KeyEvent evt) {                                   
                char input = evt.getKeyChar();
            if(!Character.isDigit(input)){
                evt.consume(); // Hanya angka yang diperbolehkan
            }    // TODO add your handling code here:
            }                                  

            private void txtAngka2KeyTyped(java.awt.event.KeyEvent evt) {                                   
                char input = evt.getKeyChar();
            if(!Character.isDigit(input)){
                evt.consume(); // Hanya angka yang diperbolehkan
            }          // TODO add your handling code here:
            }                                  

            private void txtAngka1FocusGained(java.awt.event.FocusEvent evt) {                                      
                txtAngka1.setText("");        // TODO add your handling code here:
            }                                     

            /**
            * @param args the command line arguments
            */
            public static void main(String args[]) {
                /* Set the Nimbus look and feel */
                //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
                /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
                * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
                */
                try {
                    for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                        if ("Nimbus".equals(info.getName())) {
                            javax.swing.UIManager.setLookAndFeel(info.getClassName());
                            break;
                        }
                    }
                } catch (ClassNotFoundException ex) {
                    java.util.logging.Logger.getLogger(FormTambahAngka.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
                } catch (InstantiationException ex) {
                    java.util.logging.Logger.getLogger(FormTambahAngka.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
                } catch (IllegalAccessException ex) {
                    java.util.logging.Logger.getLogger(FormTambahAngka.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
                } catch (javax.swing.UnsupportedLookAndFeelException ex) {
                    java.util.logging.Logger.getLogger(FormTambahAngka.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
                }
                //</editor-fold>

                /* Create and display the form */
                java.awt.EventQueue.invokeLater(new Runnable() {
                    public void run() {
                        new FormTambahAngka().setVisible(true);
                    }
                });
            }

            // Variables declaration - do not modify                     
            private javax.swing.JButton jButton1;
            private javax.swing.JButton jButton2;
            private javax.swing.JButton jButton3;
            private javax.swing.JLabel jLabel1;
            private javax.swing.JLabel jLabel5;
            private javax.swing.JLabel jLabel6;
            private javax.swing.JLabel jLabel7;
            private javax.swing.JPanel jPanel2;
            private javax.swing.JTextField txtAngka1;
            private javax.swing.JTextField txtAngka2;
            private javax.swing.JTextField txtHasil;
            // End of variables declaration                   
        }

        ```

## Authors

- MuhammadSaputraArjunaidy
- 2210010300
- 5B Reg Pagi Banjarmasin
- [@MuhammadSaputraArjunaidy](https://www.github.com/MuhammadSaputraArjunaidy)


## Screenshot