# MERNH_FERouting

**List of Features**
1. Headers
2. Footers
3. FrontEnd Routing



#Instructions:
1. Download BootStrap Theme on Bootswatch
- Drag and Drop this to the frontend/src folder
- Import files in index.js

2. Create Header
3. Create Footer
4. Create HomeScreen & OtherScreen
Ex: 
  return (
    <BrowserRouter>
      <Header />
      <main>
        <Container>
          <Route path='/loginscreen' component={LoginScreen} />
          <Route path='/' component={HomeScreen} exact />
        </Container>
      </main>
      <Footer />
    </BrowserRouter>
  )

5. Configure App.js to add Header, Footer, HomeScreen
6. Set up Routes on App.js

Notes:
- App.js will contain parent Tag "BrowserRouter" which will contain the other routes
- If you are dealing with FE, you will definitely need to import react
