# 17-11-2024

curl myexternalip.com/raw
====================================
"RequestLoggingLevel": default da öneri; test ortamı 1, prod 4 olsun.

GO
SET QUOTED_IDENTIFIER ON
------------Temp Table-------------
CREATE TABLE #Variables(Name VARCHAR(250), Value VARCHAR(3000))
GO
-------------------CONFIG------------------

DECLARE @StoragePath NVARCHAR(3000) = N'C:\AksisStorage'
