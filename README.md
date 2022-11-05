# toolkit


** NPM INIT DEFAULT QUESTION
npm init -y

**UPDATE ALL PACKAGE IN PACKAGE.JSON

npm i -g npm-check-updates && ncu -u && npm i

**Uninstalling local packages
npm uninstall <package_name>

**Ubuntu install app with .deb extension after download
sudo dpkg -i appname.deb
// if get error related to dependency
sudo apt install -f

********JAVASCRIPT**********
--mendapatkan banyak hari dalam 1 bulan
 const getDays = () => {
        return new Date(Year, Month, 0).getDate();
 };
 // contoh
  const getDays = () => {
        return new Date(2022, 1, 0).getDate(); // mendapatkan jumlah hari pada bulan januari 2022
    };

******* MYSQL ********
1. Login to MYSQL : mysql -uroot -p
