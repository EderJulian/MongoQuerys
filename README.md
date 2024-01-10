# MongoQuerys
MongoQuerys

1.1. Desarrollar el Proyecto

use redSocial
db.createCollection("Users")
db.createCollection("Posts")
db.createCollection("Comments")



1.2.1 INSERTAR DATOS


db.Posts.insert({
  "title": "Aventuras en la naturaleza",
  "body": "Explorando bosques y montañas.",
  "username": "aventurero123",
  "comments": [
    { "username": "explorador1", "body": "¡Increíble aventura!" },
    { "username": "amante_de_la_naturaleza", "body": "Me encantaría unirme a esto." }
  ]
});

db.Posts.insert({
  "title": "Recetas caseras",
  "body": "Compartiendo mi receta secreta de lasaña.",
  "username": "chef_en_casa",
  "comments": [
    { "username": "foodie123", "body": "¡Se ve deliciosa!" },
    { "username": "cocinero_experto", "body": "¿Puedes compartir la receta?" }
  ]
});

// Publicación 3
db.Posts.insert({
  "title": "Viaje fotográfico",
  "body": "Capturando momentos inolvidables en cada imagen.",
  "username": "fotografo_viajero",
  "comments": [
    { "username": "amante_de_fotos", "body": "Tus fotos son asombrosas." },
    { "username": "viajero_entusiasta", "body": "¿Cuál fue tu lugar favorito?" }
  ]
});



db.Posts.insert({
  "title": "Consejos para la jardinería",
  "body": "Cultivando un hermoso jardín en casa.",
  "username": "jardinero_experto",
  "comments": [
    { "username": "entusiasta_de_las_plantas", "body": "¿Cómo manejas las plagas?" },
    { "username": "amante_de_la_naturaleza", "body": "Quiero empezar mi propio jardín." }
  ]
});


db.Posts.insert({
  "title": "Historias de ciencia ficción",
  "body": "Explorando mundos imaginarios y galaxias lejanas.",
  "username": "lector_de_ciencia_ficcion",
  "comments": [
    { "username": "fan_de_star_wars", "body": "¡Star Wars es mi favorito!" },
    { "username": "escritor_fantastico", "body": "¿Cuál es tu libro favorito?" }
  ]
});


db.Posts.insert({
  "title": "Excursiones de montaña",
  "body": "Explorando picos altos y valles profundos.",
  "username": "montanero_aventurero",
  "comments": [
    { "username": "senderista_entusiasta", "body": "¡Qué vistas impresionantes!" },
    { "username": "escalador_extremo", "body": "¿Has escalado alguna cumbre?" }
  ]
});


db.Posts.insert({
  "title": "Diario de un escritor",
  "body": "Compartiendo experiencias y consejos de escritura.",
  "username": "escritor_apasionado",
  "comments": [
    { "username": "lector_fiel", "body": "Me inspiras a escribir más." },
    { "username": "colega_escritor", "body": "¿Cuál es tu género favorito?" }
  ]
});




db.Posts.insert({
  "title": "Descubriendo nuevas tecnologías",
  "body": "Explorando las últimas tendencias en la industria tecnológica.",
  "username": "tecno_entusiasta",
  "comments": [
    { "username": "developer_innovador", "body": "¿Cuál es la tecnología más emocionante para ti?" },
    { "username": "apasionado_por_la_innovacion", "body": "¡Me encanta seguir las novedades!" }
  ]
});


db.Posts.insert({
  "title": "Aprendiendo a tocar la guitarra",
  "body": "Compartiendo mi viaje de aprendizaje musical.",
  "username": "musico_amateur",
  "comments": [
    { "username": "amante_de_la_musica", "body": "¡La música es una gran forma de expresión!" },
    { "username": "colega_musico", "body": "¿Qué canciones te gusta tocar?" }
  ]
});


db.Posts.insert({
  "title": "Consejos para una vida saludable",
  "body": "Hábitos diarios para mantener un estilo de vida saludable.",
  "username": "entusiasta_de_la_salud",
  "comments": [
    { "username": "fitness_fanatico", "body": "¡Me encantaría probar esos consejos!" },
    { "username": "colega_saludable", "body": "¿Tienes alguna rutina de ejercicios favorita?" }
  ]
});




db.Posts.insert({
  "title": "Viaje gastronómico",
  "body": "Explorando sabores del mundo a través de la cocina.",
  "username": "gourmet_viajero",
  "comments": [
    { "username": "food_explorer", "body": "¡Esa comida se ve deliciosa!" },
    { "username": "chef_apasionado", "body": "¿Has probado alguna cocina exótica?" }
  ]
});


db.Posts.insert({
  "title": "Desarrollo personal y mindfulness",
  "body": "Compartiendo experiencias para el crecimiento personal.",
  "username": "buscador_de_paz_interior",
  "comments": [
    { "username": "espiritual_entusiasta", "body": "¡La práctica del mindfulness es increíble!" },
    { "username": "colega_desarrollo_personal", "body": "¿Tienes algún libro recomendado?" }
  ]
});

db.Posts.insert({
  "title": "Arte callejero y expresión urbana",
  "body": "Explorando el impacto del arte en entornos urbanos.",
  "username": "urban_artist",
  "comments": [
    { "username": "fan_del_arte_urbano", "body": "¡El arte callejero siempre sorprende!" },
    { "username": "colega_artistico", "body": "¿Cuál es tu inspiración para crear?" }
  ]
});


db.Posts.insert({
  "title": "Exploración submarina",
  "body": "Descubriendo la belleza oculta del océano.",
  "username": "explorador_submarino",
  "comments": [
    { "username": "amante_del_mar", "body": "¡Las fotos submarinas son fascinantes!" },
    { "username": "colega_buceador", "body": "¿Cuál es tu lugar submarino favorito?" }
  ]
});


db.Posts.insert({
  "title": "Viaje en solitario",
  "body": "Reflexiones personales durante un viaje solitario.",
  "username": "viajero_solitario",
  "comments": [
    { "username": "aventurero_solitario", "body": "¡A veces los mejores viajes son en solitario!" },
    { "username": "colega_viajero", "body": "¿Cuál fue tu destino más memorable?" }
  ]
});




db.Users.insert({
  "username": "usuario1",
  "email": "usuario1@email.com",
  "age": 25
});


db.Users.insert({
  "username": "usuario2",
  "email": "usuario2@email.com",
  "age": 30
});


db.Users.insert({
  "username": "usuario3",
  "email": "usuario3@email.com",
  "age": 28
});


db.Users.insert({
  "username": "usuario4",
  "email": "usuario4@email.com",
  "age": 22
});


db.Users.insert({
  "username": "usuario5",
  "email": "usuario5@email.com",
  "age": 35
});


db.Users.insert({
  "username": "usuario6",
  "email": "usuario6@email.com",
  "age": 27
});


db.Users.insert({
  "username": "usuario7",
  "email": "usuario7@email.com",
  "age": 29
});


db.Users.insert({
  "username": "usuario8",
  "email": "usuario8@email.com",
  "age": 32
});


db.Users.insert({
  "username": "usuario9",
  "email": "usuario9@email.com",
  "age": 26
});


db.Users.insert({
  "username": "usuario10",
  "email": "usuario10@email.com",
  "age": 31
});





1.2.2 ACTUALIZAR DATOS

db.Posts.update(
   { "title": "Aventuras en la naturaleza" },
   {
     "title": "Nuevas aventuras en la naturaleza",
     "body": "Explorando bosques, montañas y ríos.",
     "username": "aventurero123",
     "comments": [
       { "username": "explorador1", "body": "¡Increíble experiencia al aire libre!" },
       { "username": "amante_de_la_naturaleza", "body": "Me encantaría unirme a esto." }
     ]
   }
);



db.Posts.update(
   { "title": "Recetas caseras" },
   { $set: { "body": "Compartiendo mi receta secreta de lasaña. ¡Espero que la disfruten!" } }
);



db.Comments.update(
   { "title": "Historias de ciencia ficción", "comments.username": "fan_de_star_wars" },
   { $set: { "comments.$.body": "¡Me encanta Star Wars! ¿Cuál es tu episodio favorito?" } }
);




db.Users.update(
   { "username": "usuario1" },
   {
     $set: {
       "username": "nuevo_usuario1",
       "email": "nuevo_usuario1@email.com",
       "age": 28
     }
   }
);

db.Users.update(
   { "username": "usuario2" },
   { $set: { "email": "nuevo_email_usuario2@email.com" } }
);

db.Users.update(
   { "username": "usuario3" },
   { $set: { "email": "nuevo_email_usuario3@email.com" } }
);

db.Users.update(
   { "username": "usuario4" },
   { $inc: { "age": 5 } }
);



1.2.3 OBTENER DATOS

db.Posts.find({});



db.Posts.find({ "username": "usuario1" });



db.Users.find({ "age": { $gt: 20 } });



db.Users.find({ "age": { $lt: 23 } });



db.Users.find({ "age": { $gte: 25, $lte: 30 } });




db.Users.find().sort({ "age": 1 });


db.Users.find().sort({ "age": -1 });



db.Users.find().count();



db.Posts.find({}, { "title": 1, "_id": 0 });



db.Users.find().limit(2);



db.Posts.find({ "title": { $regex: /keyword/i } }).limit(2);




1.2.4 BORRAR DATOS

db.Users.remove({ "age": { $gt: 30 } });



