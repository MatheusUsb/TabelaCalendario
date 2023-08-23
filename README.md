# TabelaCalendario

-- Criação da tabela de calendário
CREATE TABLE calendario (
    id INT PRIMARY KEY,
    data DATE,
    dia_semana VARCHAR(10),
    mes INT,
    ano INT
);

-- Inserção dos dados do calendário de 2023 (Janeiro a Dezembro)
INSERT INTO calendario (id, data, dia_semana, mes, ano)
VALUES
    (1, '2023-01-01', 'Domingo', 1, 2023),
    -- ... (continue inserindo os dados para os outros dias do ano)
    (365, '2023-12-31', 'Domingo', 12, 2023);
