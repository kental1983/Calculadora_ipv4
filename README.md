{
    "name": "kental/Calculador_ipv4",
    "description": "Descrição do seu projeto",
    "require": {
        "php": "^7.4 || ^8.0"  // Ajuste a versão do PHP conforme necessário
    },
    "require-dev": {
        "phpunit/phpunit": "^9.5"  // Adicione o PHPUnit como dependência de desenvolvimento
    },
    "scripts": {
        "test": "vendor/bin/phpunit"  // Script para rodar os testes
    },
    "autoload": {
        "psr-4": {
            "App\\": "src/"  // Ajuste para o seu namespace e diretório
        }
    },
    "autoload-dev": {
        "psr-4": {
            "Tests\\": "tests/"  // Ajuste para o seu namespace de testes
        }
    }
}
