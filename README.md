Buat Database :
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL UNIQUE,
    phone VARCHAR(15) NOT NULL,
    password VARCHAR(255) NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);


**CARA MASUK KE REGISTER DENGAN MEMBUKA FILE REGISTER.HTML LALU NANTI AKAN LANJUT KE LOGIN.HTML LALU MASUK KE DASHBOARD.PHP**
