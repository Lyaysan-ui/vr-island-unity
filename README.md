# VR Island

Учебный VR-проект на Unity: остров с водой и перемещением по сцене в виртуальной реальности.

## Что реализовано

- управление в VR через XR Interaction Toolkit 2.6.4 и OpenXR;
- телепортация лучом, включаемая по вводу (`ActivationTeleportationRay.cs`);
- анимация виртуальных рук по нажатиям триггера и граба на контроллере (`Scripts/AnimateHandOnInput.cs`);
- сцена острова (`Assets/Scenes/SampleScene.unity`).

## Стек

Unity, C#, XR Interaction Toolkit, OpenXR, Input System.

## Важно

В репозиторий включены только мои скрипты, сцена, настройки проекта и список пакетов.
Сторонние ассеты (шейдеры воды, модели рук, Standard Assets, Mini First Person Controller, примеры XRI)
не публикуются из-за лицензий, поэтому сцена откроется с пропущенными ссылками —
их нужно добавить из Asset Store / Package Manager.
