# Around-Web
This is a frontend project mainly focused on React. It aims to allow users to post pictures and messages and share on the map based on their locations.

## demo
https://drive.google.com/file/d/12Eg0fEwgnKpjnlgUi9C10dTfSe2jSSIL/view

## code
The code is divided into four parts, assets, components, styles and tests. <br />
I mainly focused on components part. This part provides all the functionality for this project. <br />

1. App component handels login and logout based on token key. App contains components Header and Main. <br />

2. Main component uses browser router to map login, register and home component and enables switch between them. <br />

3. Home component mainly consists of post gallery and map. <br />

4. AroundMap and AroundMarker components make the map could adjust according to the map changes (zoom or drag) and shows posts when your mouse on the marker. <br />

5. CreatPostButton and CreatPostForm help us to upload our posts.<br />
