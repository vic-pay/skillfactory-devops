# Репозиторий для заданий курса Skillfactory: DevOps

# Техническое задание
Цель: настройка CI/CD системы для сборки, тестирования и установки прикладного программного обеспечения в изделии заказчика

Задачи: 
- выбрать ПО для организации CI/CD;
- установить ПО; 
- разработать pipeline для: получения исходного кода из репозитория, компиляции, запуска тестов и установки скомпилированного ПО в тестовую среду;
- настроить учетные записи в репозитории и тестовой среде в соответствии с минимально необходимыми полномочиями;
- автоматизировать процесс развертывания CI/CD системы.

Критерии оценки:
- CI/CD система должна выполнять описанный выше pipeline автоматически или по команде оператора;
- CI/CD система должна быть совместима с ОС Ubuntu и ОС СН Astra Linux Special Edition 1.6;
- CI/CD система должна быть совместима с репозиторием GIT;
- CI/CD система должна функционировать в контейнере LXC или LXD.

Требуемые ресурсы: 
предоставление заказчиком следующих сведений:
- структуры репозитория;
- IP-адресов в тестовой среде.
выделение ЭВМ на территории заказчика для размещения CI/CD системы.

Риски: в случае невозможности использования CI/CD системы необходимо автоматизировать процесс установки ПО в тестовую среду
Данное решение соответствует текущим трендам и не несет рисков от влияния трендов

# SWOT анализ

# Алгоритм работы CI/CD системы 
