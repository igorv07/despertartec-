CREATE DATABASE db_tabelaprodutos;


USE db_tabelaprodutos;

create table tb_tabelaprodutos (
id bigint auto_increment,
produtos varchar (200),
cliente varchar (50),
categoria varchar (50),
preço varchar (10),
codigo varchar (10),
primary key (id)
);

INSERT INTO tb_tabelaprodutos (produtos, cliente, categoria, preço, codigo) VALUES ("feijão", "joão", "alimentos", "10,50$", "X1");
INSERT INTO tb_tabelaprodutos (produtos, cliente, categoria, preço, codigo) VALUES ("sabão em pó", "alex", "limpeza", "20,00$", "X2");
INSERT INTO tb_tabelaprodutos (produtos, cliente, categoria, preço, codigo) VALUES ("macarrão", "bruno", "alimentos", "4,00$", "X3");
INSERT INTO tb_tabelaprodutos (produtos, cliente, categoria, preço, codigo) VALUES ("amaciante", "bruna", "limpeza", "18,00$", "X4");
INSERT INTO tb_tabelaprodutos (produtos, cliente, categoria, preço, codigo) VALUES ("frango", "luiz", "alimentos", "14,90$", "X5");
INSERT INTO tb_tabelaprodutos (produtos, cliente, categoria, preço, codigo) VALUES ("bolacha", "antonio", "alimentos", "3,50$", "X6");






CREATE TABLE tb_tabelacliente (
id bigint auto_increment,
codigo varchar (100),
nomecliente varchar (100),
endereço varchar (200),
telefone varchar (40),
statuscliente varchar (40),
limitecredito varchar (10000),
primary key (id)
);

INSERT INTO tb_tabelacliente (codigo, nomecliente, endereço, telefone, statuscliente, limitecredito ) VALUES ("XPS", "joão", "cupecê", "(11)98873-3645", "BOM", "1200,00");
INSERT INTO tb_tabelacliente (codigo, nomecliente, endereço, telefone, statuscliente, limitecredito ) VALUES ("JPS", "alex", "montemor", "(11)99382-3822", "BOM", "900,00");
INSERT INTO tb_tabelacliente (codigo, nomecliente, endereço, telefone, statuscliente, limitecredito ) VALUES ("GHJ", "bruno", "jardim miriam", "(11)93557-2232", "MEDIO", "1000,00");
INSERT INTO tb_tabelacliente (codigo, nomecliente, endereço, telefone, statuscliente, limitecredito ) VALUES ("FJD", "bruna", "campinas", "(11)92232-1882", "BOM", "780,00");
INSERT INTO tb_tabelacliente (codigo, nomecliente, endereço, telefone, statuscliente, limitecredito ) VALUES ("JJS", "luiz", "bahia", "(73)94483-2212", "BOM", "889,90");
INSERT INTO tb_tabelacliente (codigo, nomecliente, endereço, telefone, statuscliente, limitecredito ) VALUES ("KSL", "antonio", "paulista", "(11)93473-7586", "BOM", "2000,00");

CREATE table tb_infopedido  (
id bigint auto_increment,
codigopedido varchar (200),
datapedido varchar (100),
categoria2 varchar (100),
nomecliente2 varchar (100),
endereço2 varchar (100),
telefone2 varchar (200),
primary key (id)
);

INSERT INTO tb_infopedido (codigopedido, datapedido, categoria2, nomecliente2, endereço2, telefone2) VALUES ("X1", "10/05/2023", "alimento", "joão", "cupece", "(11)98873-3645");
INSERT INTO tb_infopedido (codigopedido, datapedido, categoria2, nomecliente2, endereço2, telefone2) VALUES ("X2", "13/05/2023", "limpeza", "alex", "montemor", "(11)99382-3822");
INSERT INTO tb_infopedido (codigopedido, datapedido, categoria2, nomecliente2, endereço2, telefone2) VALUES ("X3", "08/05/2023", "alimento", "bruno", "jd miriam", "(11)98873-3645");
INSERT INTO tb_infopedido (codigopedido, datapedido, categoria2, nomecliente2, endereço2, telefone2) VALUES ("X4", "07/05/2023", "limpeza", "bruna", "campinas", "(11)92232-1882");
INSERT INTO tb_infopedido (codigopedido, datapedido, categoria2, nomecliente2, endereço2, telefone2) VALUES ("X5", "15/05/2023", "alimento", "luiz", "bahia", "(73)94483-2212");
INSERT INTO tb_infopedido (codigopedido, datapedido, categoria2, nomecliente2, endereço2, telefone2) VALUES ("X6", "10/05/2023", "alimento", "antonio", "av paulista", "(11)93473-7586");










