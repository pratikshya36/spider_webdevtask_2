 CREATE USER 'prof_admin'@'localhost' IDENTIFIED BY 'prof1234';
GRANT ALL PRIVILEGES ON md5_password.* TO 'prof_admin'@'localhost'   WITH GRANT OPTION;
FLUSH PRIVILAGES;
