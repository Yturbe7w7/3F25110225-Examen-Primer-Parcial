
    ¿Qué tipo de relación existe entre "Vehículo" y "Camioneta" ¿Es herencia, agregación o asociación?
    es herencia
    
    ¿Cómo se representa la restricción de que un cliente solo puede alquilar un máximo de tres vehículos?
cliente "1" *-- "1..3" vehiculos
   
    ¿Qué modificadores de acceso serían adecuados para los atributos de cada clase?
    para *-- privados
    para o-- y --|> publicos