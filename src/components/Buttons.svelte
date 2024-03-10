<!-- Button trigger modal -->
<div class="d-flex justify-content-center align-items-center mt-5">
    <button type="button" class="btn btn-primary m-3" data-bs-toggle="modal" data-bs-target="#exampleModal">
        Register User
      </button>
    
      <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal2">
        Transfer token
      </button>
</div>
  
  <!-- Modal -->
  <div class="modal modal-dialog modal-dialog-centered fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="exampleModalLabel">Register User</h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
            <div class="input-group mb-3">
                <span class="input-group-text" id="inputGroup-sizing-default">account address</span>
                <input type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
              </div>
              
              <div class="input-group mb-3">
                <span class="input-group-text" id="inputGroup-sizing-default">Phone number</span>
                <input type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
              </div>
        </div>
        <div class="modal-footer">
            <button type="button" class="btn btn-primary">Register</button>
        </div>
      </div>
    </div>
  </div>


  <div class="modal modal-dialog modal-dialog-centered fade" id="exampleModal2" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="exampleModalLabel">Transfer</h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
            <div class="input-group mb-3">
                <span class="input-group-text" id="inputGroup-sizing-default">to</span>
                <input type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
              </div>
              
              <div class="input-group mb-3">
                <span class="input-group-text" id="inputGroup-sizing-default">amount</span>
                <input type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
              </div>
        </div>
        <div class="modal-footer">
            <button type="button" class="btn btn-primary">Transfer</button>
        </div>
      </div>
    </div>
  </div>