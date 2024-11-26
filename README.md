RestorePI - Restauración de configuración de fábrica para Raspbian
Versión: 1.0
Autor: Vikingoldier

Español
Descripción
RestorePI es un script diseñado para devolver tu sistema Raspbian a su estado de fábrica de manera rápida y automatizada. Elimina configuraciones personalizadas, datos personales y programas instalados manualmente, dejando el sistema limpio y funcional.

¿Por qué usar RestorePI?
Mantenimiento: Si el sistema no funciona correctamente y prefieres evitar una reinstalación completa.
Transferencia de dispositivo: Ideal para limpiar un sistema antes de entregarlo a otra persona.
Pruebas y desarrollo: Perfecto para desarrolladores que necesitan un entorno limpio para empezar nuevos proyectos.
Instrucciones de uso
Código
sudo su

Código

mkdir /tmp/restorepi
cd /tmp/restorepi

Código

wget https://github.com/VikingRestorePI/restorepi.sh

Código

chmod +xrestorepi.sh

Código

sudo ./restorepi.sh

Advertencias
Haz un respaldo: Este script elimina datos de forma permanente. Realiza una copia de seguridad antes de usarlo.
Lee la documentación: Asegúrate de comprender los pasos y riesgos antes de ejecutarlo.
Uso bajo tu responsabilidad: Ni Vikingoldier ni la comunidad se hacen responsables del uso indebido o de problemas derivados de una mala comprensión del script.
Licencia y créditos
RestorePI es un proyecto de código abierto creado por Vikingoldier. Se permite su uso, modificación y redistribución con atribución al autor original.

Nota: Este script se proporciona "tal cual", sin garantía alguna. Úselo bajo su propio riesgo.

---------------------------------------------------------------------------------------------------------------

English

---------------------------------------------------------------------------------------------------------------
Description
RestorePI is a script designed to quickly and automatically restore your Raspbian system to its factory state. It removes custom configurations, personal data, and manually installed programs, leaving the system clean and functional.

Why use RestorePI?
Maintenance: If the system is malfunctioning and you want to avoid a full reinstallation.
Device transfer: Perfect for wiping a system before giving it to someone else.
Testing and development: Great for developers needing a clean environment for new projects.
Usage Instructions
Code
sudo su

Code

mkdir /tmp/restorepi
cd /tmp/restorepi

Code

wget https://github.com/VikingRestorePI/restorepi.sh

Code

chmod +x restorepi.sh

Code

sudo ./restorepi.sh

Warnings
Back up your data: This script permanently deletes data. Make sure to back up any important files before running it.
Read the documentation: Ensure you understand the steps and risks before proceeding.
Use at your own risk: Neither Vikingoldier nor the community is responsible for misuse or misunderstandings of this script.
License and Credits
RestorePI is an open-source project created by Vikingoldier. It can be used, modified, and redistributed with proper attribution to the original author.

Note: This script is provided "as is," without any warranty. Use at your own risk.

---------------------------------------------------------------------------------------------------------------

Русский

---------------------------------------------------------------------------------------------------------------
Описание
RestorePI — это скрипт, предназначенный для быстрого и автоматического восстановления системы Raspbian до заводского состояния. Он удаляет пользовательские настройки, личные данные и вручную установленные программы, оставляя систему чистой и функциональной.

Почему использовать RestorePI?
Обслуживание: Если система работает неправильно, а вы хотите избежать полной переустановки.
Передача устройства: Идеально подходит для очистки системы перед передачей другому пользователю.
Тестирование и разработка: Отличный инструмент для разработчиков, нуждающихся в чистой среде для новых проектов.
Инструкции по использованию
Код
sudo su

Код

mkdir /tmp/restorepi
cd /tmp/restorepi

Код

wget https://github.com/VikingRestorePI/restorepi.sh

Код

chmod +x restorepi.sh

Код

sudo ./restorepi.sh

Предупреждения
Сделайте резервную копию: Этот скрипт безвозвратно удаляет данные. Убедитесь, что вы сделали резервную копию важных файлов.
Прочитайте документацию: Убедитесь, что вы понимаете шаги и риски перед запуском.
Используйте на свой страх и риск: Vikingoldier и сообщество не несут ответственности за неправильное использование или ошибки в понимании данного скрипта.
Лицензия и авторство
RestorePI — это проект с открытым исходным кодом, созданный Vikingoldier. Вы можете использовать, модифицировать и распространять его с обязательным указанием автора.

Примечание: Скрипт предоставляется «как есть», без каких-либо гарантий. Используйте его на свой страх и риск.

---------------------------------------------------------------------------------------------------------------

中文

---------------------------------------------------------------------------------------------------------------

描述
RestorePI 是一个脚本，旨在快速自动地将你的 Raspbian 系统恢复到出厂状态。它会删除自定义配置、个人数据和手动安装的程序，让系统恢复干净和功能齐全。

为什么使用 RestorePI？
维护： 如果系统出现问题，又想避免完全重新安装。
设备转移： 非常适合在将系统交给他人之前进行清理。
测试和开发： 对于需要干净环境的新项目开发者来说，这是一个很棒的工具。
使用说明
代码
sudo su

代码

mkdir /tmp/restorepi
cd /tmp/restorepi

代码

wget https://github.com/VikingRestorePI/restorepi.sh

代码

chmod +x restorepi.sh

代码

sudo ./restorepi.sh

警告
备份数据： 此脚本会永久删除数据。运行前请备份重要文件。
阅读文档： 在执行前，请确保你理解步骤和风险。
后果自负： Vikingoldier 和社区对脚本的误用或误解不承担责任。
许可和归属
RestorePI 是由 Vikingoldier 创建的开源项目。允许在注明原作者的情况下使用、修改和分发。

注意： 本脚本按“原样”提供，不提供任何保证。使用风险自担。


---------------------------------------------------------------------------------------------------------------

한국어

---------------------------------------------------------------------------------------------------------------

설명
RestorePI는 Raspbian 시스템을 공장 초기 상태로 빠르고 자동으로 복원하도록 설계된 스크립트입니다. 사용자 정의 구성, 개인 데이터 및 수동으로 설치된 프로그램을 제거하여 시스템을 깨끗하고 기능적으로 만듭니다.

RestorePI를 사용해야 하는 이유?
유지 관리: 시스템이 제대로 작동하지 않을 때 전체 재설치를 피하고 싶을 때.
장치 이전: 장치를 다른 사람에게 전달하기 전에 시스템을 지우기에 적합.
테스트 및 개발: 새로운 프로젝트를 위한 깨끗한 환경이 필요한 개발자들에게 이상적.
사용 지침
코드
sudo su

코드

mkdir /tmp/restorepi
cd /tmp/restorepi

코드

wget https://github.com/VikingRestorePI/restorepi.sh

코드

chmod +x restorepi.sh

코드

sudo ./restorepi.sh

경고
데이터 백업: 이 스크립트는 데이터를 영구적으로 삭제합니다. 실행 전에 중요한 파일을 백업하세요.
문서 읽기: 실행하기 전에 단계와 위험을 충분히 이해했는지 확인하세요.
책임: Vikingoldier와 커뮤니티는 잘못된 사용이나 스크립트 오해로 인한 결과에 대해 책임지지 않습니다.
라이선스 및 크레딧
RestorePI는 Vikingoldier가 만든 오픈 소스 프로젝트입니다. 원 저작자를 명시하는 조건으로 사용, 수정 및 배포할 수 있습니다.

주의: 이 스크립트는 "있는 그대로" 제공되며 보증이 없습니다. 사용에 따른 모든 책임은 사용자에게 있습니다.
