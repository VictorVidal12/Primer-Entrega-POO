# Primer-Entrega-POO
from dataclasses import dataclass

@dataclass
class Universidad:



class Monitor:
    nombre: str
    idMonitor: str
    contraseñaMonitor: str

class Usuario:
    idUsuario: str
    contraseña: str

class asesoriasMonitores:
    horario: str
    materia: str
    monitor: str
    dia: str
    salon: str
    idMonitoresR: str
    contraseñaMonitoresR: str


class Semestre:
    numero_semestre: int
    materias: list = []
    matricula: float

class asesoriasEstudiantes:
    horario: str
    materia: str
    monitor: str
    valor: int
    dia: str
    salon: str
    cantidad_estudiantes: int
    idEstudR: str
    contraseñaEstudR: str
    cambiar_asesoria: str

    def verificar_usuario(self, Usuario.idUsuario, Usuario.contraseña)->bool:
    if Usuario.idUsuario == idEstudR:
        return True
        if Usuario.contraseña == contraseñaEstudR:
            return True,print("Has iniciado sesión con éxito")
        else:
            return False, print("Contraseña inválida")
    else:
        return False, print("Usuario no registrado")

    def verificar_materia(self,Semestre.materias,materia)->bool:
        for j in range (Semestre.materias):
            if not j==materia:
                return False, print("No hay asesorías disponibles para esa materia")
            else:
                return True

    def asesorias_disponibles(monitor, horario, dia, salon):
        if asesoriasEstudiantes.verificar_materia = True:
            asesorias_disp=[(materia,monitor,horario,dia,salon)]
            print(asesorias_disp)

    def agendar_asesoria(materias,asesorias_disp):



    def verificar_horario_salon(horario, salon, valor):
        continuar=str(input("La asesoría será en el salón",salon,"a las",horario,"¿deseas continuar? (seguir el proceso o cambiar)")
        if continuar == "seguir el proceso":
            pagar=str(input("El precio es de:",valor,"¿desea pagarlo? (si o no)")
            if pagar == "si":
                metodo_de_pago=str(input("Elegir método de pago Virtual o Presencial"))
                if metodo_de_pago=="Virtual":
                    valor_total=valor_total-valor
                    print("Tu carrito ha quedado con", valor_total,"y has pagado con éxito")
                    #tener en cuenta que el método para calcular el valor_total todavía no se ha definido.
                else:
                    print("Por favor dirigirse hacia las secretarias del bloque administrativo")
            else:
                print(asesorias_disp)
        else:
            cambiar_asesoria=str(input("Si está seguro, continuar"))
            if cambiar_asesoria="seguro":
                print(asesorias_disp)


class Carrito:
    valor_total: int
    cantidad_asesorias: int
    asesorias_agendadas: list
    valor_multa: int
    asesorias_pagadas: int
