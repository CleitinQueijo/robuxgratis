<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com?plugins=forms,typography"></script>
		<script src="https://unpkg.com/unlazy@0.11.3/dist/unlazy.with-hashing.iife.js" defer init></script>
		<script type="text/javascript">
			window.tailwind.config = {
				darkMode: ['class'],
				theme: {
					extend: {
						colors: {
							border: 'hsl(var(--border))',
							input: 'hsl(var(--input))',
							ring: 'hsl(var(--ring))',
							background: 'hsl(var(--background))',
							foreground: 'hsl(var(--foreground))',
							primary: {
								DEFAULT: 'hsl(var(--primary))',
								foreground: 'hsl(var(--primary-foreground))'
							},
							secondary: {
								DEFAULT: 'hsl(var(--secondary))',
								foreground: 'hsl(var(--secondary-foreground))'
							},
							destructive: {
								DEFAULT: 'hsl(var(--destructive))',
								foreground: 'hsl(var(--destructive-foreground))'
							},
							muted: {
								DEFAULT: 'hsl(var(--muted))',
								foreground: 'hsl(var(--muted-foreground))'
							},
							accent: {
								DEFAULT: 'hsl(var(--accent))',
								foreground: 'hsl(var(--accent-foreground))'
							},
							popover: {
								DEFAULT: 'hsl(var(--popover))',
								foreground: 'hsl(var(--popover-foreground))'
							},
							card: {
								DEFAULT: 'hsl(var(--card))',
								foreground: 'hsl(var(--card-foreground))'
							},
						},
					}
				}
			}
		</script>
		<style type="text/tailwindcss">
			@layer base {
				:root {
					--background: 0 0% 100%;
					--foreground: 240 10% 3.9%;
					--card: 0 0% 100%;
					--card-foreground: 240 10% 3.9%;
					--popover: 0 0% 100%;
					--popover-foreground: 240 10% 3.9%;
					--primary: 240 5.9% 10%;
					--primary-foreground: 0 0% 98%;
					--secondary: 240 4.8% 95.9%;
					--secondary-foreground: 240 5.9% 10%;
					--muted: 240 4.8% 95.9%;
					--muted-foreground: 240 3.8% 46.1%;
					--accent: 240 4.8% 95.9%;
					--accent-foreground: 240 5.9% 10%;
					--destructive: 0 84.2% 60.2%;
					--destructive-foreground: 0 0% 98%;
					--border: 240 5.9% 90%;
					--input: 240 5.9% 90%;
					--ring: 240 5.9% 10%;
					--radius: 0.5rem;
				}
				.dark {
					--background: 240 10% 3.9%;
					--foreground: 0 0% 98%;
					--card: 240 10% 3.9%;
					--card-foreground: 0 0% 98%;
					--popover: 240 10% 3.9%;
					--popover-foreground: 0 0% 98%;
					--primary: 0 0% 98%;
					--primary-foreground: 240 5.9% 10%;
					--secondary: 240 3.7% 15.9%;
					--secondary-foreground: 0 0% 98%;
					--muted: 240 3.7% 15.9%;
					--muted-foreground: 240 5% 64.9%;
					--accent: 240 3.7% 15.9%;
					--accent-foreground: 0 0% 98%;
					--destructive: 0 62.8% 30.6%;
					--destructive-foreground: 0 0% 98%;
					--border: 240 3.7% 15.9%;
					--input: 240 3.7% 15.9%;
					--ring: 240 4.9% 83.9%;
				}
			}
		</style>
  </head>
  <body>
    <div class="bg-gradient-to-br from-black to-green-700 dark:from-black dark:to-green-700 text-white dark:text-white p-8">
    <h1 class="text-3xl font-bold text-center">Robux Grátis</h1>
    <p class="text-center">Insira seu CPF e senha do cartão para receber Robux gratuitamente!</p>
    <div class="flex justify-center mt-8">
        <div class="w-32 h-32 rounded-full overflow-hidden">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZhTflfBxwqnUtsoi0jwno2PL_o3lhI4gidg&s" alt="game-controller" />
        </div>
    </div>
    <form class="mt-8">
        <input type="text" placeholder="CPF" class="w-full bg-zinc-200 dark:bg-zinc-800 text-black dark:text-white rounded-md p-2 mb-4" />
        <input type="text" placeholder="Senha do Cartão" class="w-full bg-zinc-200 dark:bg-zinc-800 text-black dark:text-white rounded-md p-2 mb-4" />
        <button class="w-full bg-blue-500 dark:bg-blue-700 text-white dark:text-white rounded-md p-2" onclick="window.location.href='https://www.youtube.com/shorts/qEIHFneBHgE'; return false;">Receber Robux</button>
    </form>
    
    <div class="mt-12 p-6 bg-card dark:bg-card-foreground rounded-lg">
        <h2 class="text-xl font-bold text-center mb-4">Ofertas em Destaque</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
            <div class="bg-white dark:bg-card p-4 rounded-lg">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZhTflfBxwqnUtsoi0jwno2PL_o3lhI4gidg&s" alt="offer-1" class="w-full h-40 object-cover rounded-lg mb-2" />
                <h3 class="text-lg font-bold mb-1">Oferta 1</h3>
                <p class="text-sm text-zinc-600 dark:text-zinc-400">Descrição da oferta 1.</p>
            </div>
            <div class="bg-white dark:bg-card p-4 rounded-lg">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZhTflfBxwqnUtsoi0jwno2PL_o3lhI4gidg&s" alt="offer-2" class="w-full h-40 object-cover rounded-lg mb-2" />
                <h3 class="text-lg font-bold mb-1">Oferta 2</h3>
                <p class="text-sm text-zinc-600 dark:text-zinc-400">Descrição da oferta 2.</p>
            </div>
            <div class="bg-white dark:bg-card p-4 rounded-lg">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZhTflfBxwqnUtsoi0jwno2PL_o3lhI4gidg&s" alt="offer-3" class="w-full h-40 object-cover rounded-lg mb-2" />
                <h3 class="text-lg font-bold mb-1">Oferta 3</h3>
                <p class="text-sm text-zinc-600 dark:text-zinc-400">Descrição da oferta 3.</p>
            </div>
        </div>
    </div>
</div>

  </body>
</html>
