<script lang="ts">
  //import { enhance } from "$lib/actions/form";

  //export let todo: Todo;
  //export let processDeletedTodoResult: (res: Response) => void;
  //export let processUpdatedTodoResult: (res: Response) => void;
</script>



<div class="todo" >
  <form  method="post" >
    <input type="hidden" name="done" />
    <button aria-label="Mark todo as/not done" class="toggle"></button>
  </form>

  <form  method="post" class="text" >
    <input type="text" name="text" />
    <button aria-label="Save todo" class="save"></button>
  </form>
  
  <form  method="post" >
    <button aria-label="Delete todo" class="delete"></button>
  </form>
</div>