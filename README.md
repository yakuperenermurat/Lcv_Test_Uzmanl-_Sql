
# test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

    CREATE TABLE employee (
        id INTEGER PRIMARY KEY,
        full_name VARCHAR(50),
        birthday DATE,
        email VARCHAR(100)
    );

# Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

    insert into employee (id, full_name, birthday, email) values (1, 'Cleo', '2024-06-22', 'cbernadot0@wsj.com');
    insert into employee (id, full_name, birthday, email) values (2, 'Lyn', '2024-10-02', 'ldavidek1@yandex.ru');
    insert into employee (id, full_name, birthday, email) values (3, 'Abagail', '2024-05-25', 'awaddam2@weebly.com');
    insert into employee (id, full_name, birthday, email) values (4, 'John', '2024-04-10', 'jblackney3@paypal.com');
    insert into employee (id, full_name, birthday, email) values (5, 'Skipton', '2024-05-02', 'sbromont4@tamu.edu');
    insert into employee (id, full_name, birthday, email) values (6, 'Rafael', '2024-07-08', 'rgatesman5@state.gov');
    insert into employee (id, full_name, birthday, email) values (7, 'Dareen', '2024-07-05', 'dmalloy6@cloudflare.com');
    insert into employee (id, full_name, birthday, email) values (8, 'Norean', '2024-03-29', 'npeteri7@sciencedaily.com');
    insert into employee (id, full_name, birthday, email) values (9, 'Marice', '2024-06-26', 'mlesurf8@time.com');
    insert into employee (id, full_name, birthday, email) values (10, 'Rosina', '2024-05-07', 'rjouannot9@engadget.com');
    insert into employee (id, full_name, birthday, email) values (11, 'Grover', '2024-01-23', 'gstevensona@sciencedirect.com');
    insert into employee (id, full_name, birthday, email) values (12, 'Cele', '2024-11-27', 'craesideb@japanpost.jp');
    insert into employee (id, full_name, birthday, email) values (13, 'Abbe', '2024-12-23', 'apaolettoc@freewebs.com');
    insert into employee (id, full_name, birthday, email) values (14, 'Currie', '2024-12-27', 'chumbled@ebay.co.uk');
    insert into employee (id, full_name, birthday, email) values (15, 'Anastasia', '2024-02-23', 'ashirlawe@ask.com');
    insert into employee (id, full_name, birthday, email) values (16, 'Florrie', '2024-03-11', 'fshillidayf@discuz.net');
    insert into employee (id, full_name, birthday, email) values (17, 'Roarke', '2024-11-26', 'rlorenzg@discovery.com');
    insert into employee (id, full_name, birthday, email) values (18, 'Heda', '2024-02-20', 'hriglesfordh@google.com.hk');
    insert into employee (id, full_name, birthday, email) values (19, 'Salomone', '2024-03-07', 'sbassindalei@google.de');
    insert into employee (id, full_name, birthday, email) values (20, 'Edsel', '2024-07-13', 'emcilmoriej@wisc.edu');
    insert into employee (id, full_name, birthday, email) values (21, 'Lenna', '2024-08-03', 'lyuryatink@google.es');
    insert into employee (id, full_name, birthday, email) values (22, 'Ariel', '2024-12-24', 'atillel@pagesperso-orange.fr');
    insert into employee (id, full_name, birthday, email) values (23, 'Hadrian', '2024-07-14', 'hwrassellm@liveinternet.ru');
    insert into employee (id, full_name, birthday, email) values (24, 'Meade', '2024-04-27', 'mroofen@google.fr');
    insert into employee (id, full_name, birthday, email) values (25, 'Candida', '2024-06-11', 'chorbarto@google.cn');
    insert into employee (id, full_name, birthday, email) values (26, 'Keelby', '2024-08-10', 'knoicep@desdev.cn');
    insert into employee (id, full_name, birthday, email) values (27, 'Rouvin', '2024-08-29', 'rstilleq@wordpress.com');
    insert into employee (id, full_name, birthday, email) values (28, 'Estell', '2024-02-13', 'ephelipeauxr@uiuc.edu');
    insert into employee (id, full_name, birthday, email) values (29, 'Waite', '2024-04-09', 'wmenslers@tmall.com');
    insert into employee (id, full_name, birthday, email) values (30, 'Zita', '2024-10-07', 'zbaistowt@tripod.com');
    insert into employee (id, full_name, birthday, email) values (31, 'Corby', '2024-01-17', 'chugou@weather.com');
    insert into employee (id, full_name, birthday, email) values (32, 'Kathy', '2024-08-10', 'kbexleyv@loc.gov');
    insert into employee (id, full_name, birthday, email) values (33, 'Salvidor', '2024-03-01', 'sswornw@howstuffworks.com');
    insert into employee (id, full_name, birthday, email) values (34, 'Francene', '2024-12-16', 'ftiptaftx@mapy.cz');
    insert into employee (id, full_name, birthday, email) values (35, 'Randie', '2024-06-27', 'rmcdilly@dion.ne.jp');
    insert into employee (id, full_name, birthday, email) values (36, 'Duky', '2024-07-16', 'dhuntressz@comsenz.com');
    insert into employee (id, full_name, birthday, email) values (37, 'Dareen', '2024-06-04', 'dkintish10@state.gov');
    insert into employee (id, full_name, birthday, email) values (38, 'Janeta', '2024-04-12', 'jjagson11@vk.com');
    insert into employee (id, full_name, birthday, email) values (39, 'Vic', '2024-10-16', 'vchaudhry12@sourceforge.net');
    insert into employee (id, full_name, birthday, email) values (40, 'Deina', '2024-01-11', 'dhindenberger13@cloudflare.com');
    insert into employee (id, full_name, birthday, email) values (41, 'Carita', '2024-09-16', 'cwoodison14@ezinearticles.com');
    insert into employee (id, full_name, birthday, email) values (42, 'Georgie', '2024-08-27', 'glayhe15@va.gov');
    insert into employee (id, full_name, birthday, email) values (43, 'Gaspard', '2024-01-18', 'gbarsam16@flavors.me');
    insert into employee (id, full_name, birthday, email) values (44, 'Gerome', '2024-04-10', 'grawlins17@constantcontact.com');
    insert into employee (id, full_name, birthday, email) values (45, 'Artur', '2024-01-22', 'akendrew18@epa.gov');
    insert into employee (id, full_name, birthday, email) values (46, 'Rick', '2024-07-13', 'rhammerman19@usa.gov');
    insert into employee (id, full_name, birthday, email) values (47, 'Thomas', '2024-10-22', 'tstraw1a@cornell.edu');
    insert into employee (id, full_name, birthday, email) values (48, 'Brandy', '2024-04-20', 'bvaneev1b@aboutads.info');
    insert into employee (id, full_name, birthday, email) values (49, 'Wilmar', '2024-07-27', 'wbeade1c@msu.edu');
    insert into employee (id, full_name, birthday, email) values (50, 'Krista', '2024-09-11', 'kdarby1d@boston.com');


# Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

       -- id'ye göre güncelleme
    UPDATE employee 
    SET full_name = 'Updated Name' 
    WHERE id = 1;
    
    -- name'e göre güncelleme
    UPDATE employee 
    SET email = 'updated.email@example.com' 
    WHERE full_name = 'Cleo';
    
    -- birthday'e göre güncelleme
    UPDATE employee 
    SET full_name = 'Birthday Updated' 
    WHERE birthday = '2024-06-22';
    
    -- email'e göre güncelleme
    UPDATE employee 
    SET birthday = '2000-01-01' 
    WHERE email = 'ldavidek1@yandex.ru';
    
    -- Belirli bir yaşın üzerindekileri güncelleme
    UPDATE employee 
    SET full_name = 'Senior Employee' 
    WHERE birthday < '1990-01-01';



# Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

    -- id'ye göre silme
    DELETE FROM employee 
    WHERE id = 5;
    
    -- name'e göre silme
    DELETE FROM employee 
    WHERE full_name = 'Charlie White';
    
    -- birthday'e göre silme
    DELETE FROM employee 
    WHERE birthday = '2024-05-25';
    
    -- email'e göre silme
    DELETE FROM employee 
    WHERE email = 'awaddam2@weebly.com';
    
    -- Belirli bir yaşın altındakileri silme
    DELETE FROM employee 
    WHERE birthday > '2024-12-31';


