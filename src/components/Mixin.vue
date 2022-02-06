<script>
import { ValidationObserver, ValidationProvider } from "vee-validate";
export default {
  name: "Mixin",

  components: {
    ValidationProvider,
    ValidationObserver,
  },
  methods: {
    resetForm() {
      this.$refs.observer.reset();
    },
  },
};
</script>
