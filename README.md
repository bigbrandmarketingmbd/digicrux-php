# 🚀 DIGICRUX - WhatsApp API Automation Platform

A professional PHP website for WhatsApp Business API with marketing, sales & support automation.

## Features

✅ WhatsApp API Integration  
✅ AI Chatbot & Automation  
✅ Broadcasting Campaigns  
✅ Payment Processing  
✅ Contact Management  
✅ Blog System  
✅ Admin Panel  
✅ Responsive Design  
✅ SEO Optimized  

## Requirements

- PHP 7.4+
- - MySQL 5.7+
  - - Apache/Nginx
    - - SSL Certificate
     
      - ## Installation
     
      - ### 1. Download & Extract
      - ```bash
        unzip digicrux-php-main.zip
        cd digicrux-php-main
        ```

        ### 2. Upload to cPanel
        - Upload to public_html
        - - Extract files
          - - Set permissions (755 for folders, 644 for files)
           
            - ### 3. Create Database
            - - cPanel → MySQL Databases
              - - Create database: `digicrux`
                - - Create user: `digicrux_user`
                  - - Grant all privileges
                   
                    - ### 4. Import Schema
                    - - phpMyAdmin → Select database → Import
                      - - Choose `database/digicrux.sql`
                        - - Click Go
                         
                          - ### 5. Configure
                          - Edit `config/config.php`:
                          - ```php
                            define('DB_HOST', 'localhost');
                            define('DB_USER', 'digicrux_user');
                            define('DB_PASS', 'your_password');
                            define('DB_NAME', 'digicrux');
                            define('SITE_URL', 'https://yourdomain.com');
                            ```

                            ### 6. Create Admin
                            Run in phpMyAdmin:
                            ```sql
                            INSERT INTO users (email, password, name, role)
                            VALUES ('admin@yourdomain.com', '$2y$10$hash', 'Admin', 'admin');
                            ```

                            ### 7. Test
                            Visit: https://yourdomain.com

                            Admin: https://yourdomain.com/admin/login.php

                            ## Project Structure

                            ```
                            ├── config/          Database & config
                            ├── includes/        Templates
                            ├── pages/          Frontend pages
                            ├── admin/          Admin panel
                            ├── api/            API endpoints
                            ├── assets/         CSS, JS, Images
                            ├── database/       SQL schema
                            └── uploads/        User files
                            ```

                            ## Support

                            Email: hello@digicrux.com
                            WhatsApp: +91 98765 43210

                            ## License

                            LGPLv2.1 License

                            ---
                            Version 1.0.0 | June 2026
