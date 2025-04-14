# N.Ivey
/* General Styles */
body {
  margin: 0;
  font-family: 'Georgia', serif;
  background-color: #fffaf4;
  color: #333;
}

header {
  background-color: #fcebd5;
  padding: 2rem 1rem;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

header h1 {
  font-size: 2.5rem;
  font-family: 'Playfair Display', serif;
  margin: 0;
  color: #8c5c2f;
}

nav {
  margin-top: 1rem;
}

nav a {
  margin: 0 1rem;
  text-decoration: none;
  color: #5a3e2b;
  font-weight: bold;
}

main {
  padding: 2rem 1rem;
  max-width: 900px;
  margin: 0 auto;
}

section {
  margin-bottom: 4rem;
}

h2 {
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  color: #6a422d;
  border-bottom: 2px solid #ecd9c6;
  padding-bottom: 0.5rem;
}

/* Author Bio */
#about {
  display: flex;
  align-items: center;
  gap: 1.5rem;
}

#about img {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  object-fit: cover;
  border: 4px solid #f7d7b4;
}

/* Gallery */
#gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 1.5rem;
}

#gallery img {
  width: 100%;
  border-radius: 1rem;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

#gallery img:hover {
  transform: scale(1.05);
}

/* Purchase Section */
#purchase a {
  display: inline-block;
  background-color: #f6b46b;
  color: white;
  padding: 0.75rem 1.5rem;
  text-decoration: none;
  font-size: 1.1rem;
  border-radius: 1rem;
  box-shadow: 0 3px 6px rgba(0,0,0,0.1);
  transition: background-color 0.3s ease;
}

#purchase a:hover {
  background-color: #eaa055;
}

/* Footer */
footer {
  text-align: center;
  padding: 2rem;
  background-color: #fcebd5;
  font-size: 0.9rem;
  color: #5a3e2b;
}
